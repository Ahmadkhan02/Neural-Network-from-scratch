# Neural-Network-from-scrath-
Implemented Convolutional Neural Network, LSTM Neural Network, and Neural Network From Scratch in Python Language. 

Convolutional Neural Network

In machine learning, a convolutional neural network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural networks that has successfully been applied to analyzing visual imagery.

CNNs use a variation of multilayer perceptrons designed to require minimal preprocessing. They are also known as shift invariant or space invariant artificial neural networks (SIANN), based on their shared-weights architecture and translation invariance characteristics.

CNNs use relatively little pre-processing compared to other image classification algorithms. This means that the network learns the filters that in traditional algorithms were hand-engineered. This independence from prior knowledge and human effort in feature design is a major advantage.

They have applications in image and video recognition, recommender systems and natural language processing.

--> Implemented Convolutional Neural Network from SCRATCH!

    Dataset : 42,000 Images of Hand Written Digtis (0-9). Each digit has around 3500-4000 Images.

    Network Architecture :

    Layers INFO :
        2 Convolution Layers
        2 Fully Connected Layers

    Filter Size :
        3x3x1x4 Filters used in Conv Layer 1
        3x3x4x16 Filters used in Conv Layee 2

    Actvation Function :
        Sigmoid
        Softmax

    Data Distribution :
        Train Set = 30,000 Images
        Cross Valid Set = 6000 Images
        Test Set = 6000 Images

    Functions Implemented using Numpy :
        Initialize Parameters
        Forward Propagation
        Cal Loss And Accuracy
        Backward Propagation
        Update Parameters

    Libraries Used :
        Numpy
        Pandas
        Matplot

    Results :
        Train Accuracy : 87%
        Valid Accuracy : 87%
        Test Accuracy : 87%

    Learned about the implementation details of forward propagation and backward propagation algorithms used in CNN's and how different activation functions affect the training accuracy.

LSTM Neural Network:

Long short-term memory (LSTM) units (or blocks) are a building unit for layers of a recurrent neural network (RNN). A RNN composed of LSTM units is often called an LSTM network. A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. The cell is responsible for "remembering" values over arbitrary time intervals; hence the word "memory" in LSTM. Each of the three gates can be thought of as a "conventional" artificial neuron, as in a multi-layer (or feedforward) neural network: that is, they compute an activation (using an activation function) of a weighted sum. Intuitively, they can be thought as regulators of the flow of values that goes through the connections of the LSTM; hence the denotation "gate". There are connections between these gates and the cell.

The expression long short-term refers to the fact that LSTM is a model for the short-term memory which can last for a long period of time. An LSTM is well-suited to classify, process and predict time series given time lags of unknown size and duration between important events. LSTMs were developed to deal with the exploding and vanishing gradient problem when training traditional RNNs.

--> Implemented LSTM Neural Network from SCRATCH!

    Dataset : US Baby's First Names

    Network Architecture :

    Actvation Function :
        Sigmoid
        Softmax
        Tanh

    Functions Implemented using Numpy :
        Initialize Parameters
        Forward Propagation
        Cal Loss And Accuracy and Perplexity
        Backward Propagation
        Update Parameters
        Update Embeddings

    Libraries Used :
        Numpy
        Pandas
        Matplot

    Results :
        Perplexity : 1.05
        Accuracy : 85%
        Awesome names predicted like -- Donald, Margaret, Harris, Isabella, William

    Learned about the implementation details of forward propagation and backward propagation through time algorithms used in RNN's and how different activation functions affect the training accuracy.

Neural Network:

Artificial neural networks (ANNs) or connectionist systems are computing systems vaguely inspired by the biological neural networks that constitute animal brains. Such systems "learn" (i.e. progressively improve performance on) tasks by considering examples, generally without task-specific programming.

An ANN is based on a collection of connected units or nodes called artificial neurons. Each connection (a simplified version of a synapse) between artificial neurons can transmit a signal from one to another. The artificial neuron that receives the signal can process it and then signal artificial neurons connected to it.

Implemented 1-hidden layer neural network for the classification of Iris Dataset. Learned about the detailed implementation of forward and backward propagation algorithms used in the neural network. Learned ways to easily compute gradients for any function.

    Dataset - Iris Dataset

    Network Architecture :

    Actvation Function :
        Sigmoid
        Softmax

    Functions Implemented using Numpy :
        Initialize Parameters
        Forward Propagation
        Cal Loss And Accuracy
        Backward Propagation
        Update Parameters
