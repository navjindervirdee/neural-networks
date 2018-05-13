# Neural-Networks
### **Implemented Convolutional Neural Network, LSTM Neural Network and Neural Network From Scratch.**

## **Convolutional Neural Network**

In machine learning, a convolutional neural network (CNN, or ConvNet) is a class of deep, feed-forward artificial neural networks that has successfully been applied to analyzing visual imagery.

CNNs use a variation of multilayer perceptrons designed to require minimal preprocessing. They are also known as shift invariant or space invariant artificial neural networks (SIANN), based on their shared-weights architecture and translation invariance characteristics.

CNNs use relatively little pre-processing compared to other image classification algorithms. This means that the network learns the filters that in traditional algorithms were hand-engineered. This independence from prior knowledge and human effort in feature design is a major advantage.

They have applications in image and video recognition, recommender systems and natural language processing.

--> **Implemented Convolutional Neural Network from SCRATCH!**
  * **Dataset** : 42,000 Images of Hand Written Digtis (0-9). Each digit has around 3500-4000 Images.
  * **Network Architecture** : 
    ![](https://github.com/navjindervirdee/neural-networks/blob/master/Convolutional%20Neural%20Network/Forward.JPG?raw=true)
    
  * **Layers INFO** :
    1. 2 Convolution Layers
    2. 2 Fully Connected Layers
    
  * **Filter Size** :
    1. 3x3x1x4  Filters used in Conv Layer 1
    2. 3x3x4x16 Filters used in Conv Layee 2
    
  * **Actvation Function** :
    1. Sigmoid
    2. Softmax
    
  * **Data Distribution** :
    1. Train Set = 30,000 Images
    2. Cross Valid Set = 6000 Images
    3. Test Set = 6000 Images
    
  * **Functions Implemented using Numpy** :
    1. Initialize Parameters
    2. Forward Propagation
    3. Cal Loss And Accuracy
    4. Backward Propagation
    5. Update Parameters
    
  * **Libraries Used** : 
    1. Numpy
    2. Pandas
    3. Matplot
    
  * **Results** :
    1. Train Accuracy : 87%
    2. Valid Accuracy : 87%
    3. Test Accuracy  : 87%
    
  * Learned about  the implementation details of forward propagation and backward propagation algorithms used in CNN's and how different       activation functions affect the training accuracy.

## **LSTM Neural Network**:

Long short-term memory (LSTM) units (or blocks) are a building unit for layers of a recurrent neural network (RNN). A RNN composed of LSTM units is often called an LSTM network. A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. The cell is responsible for "remembering" values over arbitrary time intervals; hence the word "memory" in LSTM. Each of the three gates can be thought of as a "conventional" artificial neuron, as in a multi-layer (or feedforward) neural network: that is, they compute an activation (using an activation function) of a weighted sum. Intuitively, they can be thought as regulators of the flow of values that goes through the connections of the LSTM; hence the denotation "gate". There are connections between these gates and the cell.

The expression long short-term refers to the fact that LSTM is a model for the short-term memory which can last for a long period of time. An LSTM is well-suited to classify, process and predict time series given time lags of unknown size and duration between important events. LSTMs were developed to deal with the exploding and vanishing gradient problem when training traditional RNNs.

--> **Implemented LSTM Neural Network from SCRATCH!**
* **Dataset** : US Baby's First Names
* **Network Architecture** :
![](https://github.com/navjindervirdee/neural-networks/blob/master/Recurrent%20Neural%20Network/LSTMForward.JPG?raw=true)

 * **Actvation Function** :
    1. Sigmoid
    2. Softmax
    3. Tanh
    
 * **Functions Implemented using Numpy** :
    1. Initialize Parameters
    2. Forward Propagation
    3. Cal Loss And Accuracy and Perplexity
    4. Backward Propagation
    5. Update Parameters
    6. Update Embeddings
    
  * **Libraries Used** : 
    1. Numpy
    2. Pandas
    3. Matplot
    
  * **Results** :
    1. Perplexity : 1.05
    2. Accuracy   : 85%
    3. **Awesome names predicted like -- Donald, Margaret, Harris, Isabella, William**
  * Learned about  the implementation details of forward propagation and backward propagation through time algorithms used in RNN's and how different       activation functions affect the training accuracy.

## **Neural Network**: 

Artificial neural networks (ANNs) or connectionist systems are computing systems vaguely inspired by the biological neural networks that constitute animal brains. Such systems "learn" (i.e. progressively improve performance on) tasks by considering examples, generally without task-specific programming. 

An ANN is based on a collection of connected units or nodes called artificial neurons. Each connection (a simplified version of a synapse) between artificial neurons can transmit a signal from one to another. The artificial neuron that receives the signal can process it and then signal artificial neurons connected to it.

**Implemented 1-hidden layer neural network for the classification of Iris Dataset. Learned about the detailed           implementation of forward and backward propagation algorithms used in the neural network. Learned ways to easily compute gradients for     any function.**

  * **Dataset** - Iris Dataset
  * **Network Architecture** :
    ![](https://github.com/navjindervirdee/neural-networks/blob/master/Neural%20Network/network.JPG?raw=true) 
    
  * **Actvation Function** :
    1. Sigmoid
    2. Softmax
    
  * **Functions Implemented using Numpy** :
    1. Initialize Parameters
    2. Forward Propagation
    3. Cal Loss And Accuracy
    4. Backward Propagation
    5. Update Parameters
