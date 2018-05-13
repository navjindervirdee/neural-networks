# Neural-Networks
### **Implemented Convolutional Neural Network, Neural Network From Scratch.**

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

* Currently learning and working on the Recurrent Neural Networks. 


