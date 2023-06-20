# ML-Neural Networks

## **Venture Funding Analysis**

Code is in venture_funding_with_deep_learning.ipynb notebook.  Required csv file is in the Resources folder.

* The business team has given you a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

### **Summary** ##

* 3 Neural network models were developed to predict the probability of whether a funded business would become successful based on attritbutes given in the dataset to predict "success".  116 unique attributes were extracted from the original dataset and run through 3 different neural network models.


#### **Model 1 Summary:** ####

Layers: 2

**Nodes per Layer:**

Layer 1: 58

Layer 2: 29

**Activation Function:**

Layer 1: Relu

Layer 2: Relu

**Epochs:** 50

Loss: 0.5557 

Accuracy: 0.7295



#### **Model 2 Summary:** ####

Layers: 3

**Nodes per Layer:**

Layer 1: 78

Layer 2: 52

Layer 3: 35

**Activation Function:**

Layer 1: Relu

Layer 2: Tanh

Layer 3: Sigmoid

**Epochs:** 100


Loss: 0.5549

Accuracy: 0.7282



#### **Model 3 Summary:** ####

Layers: 5

**Nodes per Layer:**

Layer 1: 78

Layer 2: 52

Layer 3: 26

Layer 2: 13

Layer 3: 7

**Activation Function:**

Layer 1: Relu

Layer 2: Relu

Layer 3: Sigmoid

Layer 4: Linear

Layer 5: Tanh

**Epochs:** 150

Loss: 0.5555

Accuracy: 0.7296

A review of the models show changes in the # of layers, # of nodes per later, type of activation function and # of epochs did very little to improve model predictive abilities.  The loss rate and accuracy rate did not change much at all so the alternative, more complex models with more runs did not add much value here.

