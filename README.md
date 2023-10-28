# Deep-Leaning
The following repository contains the handouts related with the course of Deep Learning, attended at University of Navarra where the notebook develops the use of neural networks. For this purpose, a database related to job offers for data scientist that have been published on Glassdoor has been selected.

Three different models have been applied to consider the influence of feature engineering, parameter tuning and neural network architecture:

First Model: for the first proposed model, a basic structure is chosen, with the same number of neurons in each layer except for the last one, which must correspond to the result to be obtained.

Second model: A melon-shaped arrangement of the number of neurons is used for the development of this model. This refers to an architecture in which the hidden layers have a melon-like shape, i.e., they become wider and then gradually reduce in size. It has been decided to implement this network because of the advantages it presents:

- Ability to capture complex features: it allows the neural network to have a large number of neurons in the intermediate layers, which gives it a greater ability to capture complex features and patterns in the data.

- Hierarchical feature extraction: as the hidden layers become wider and then narrower, the neural network can learn features at different levels of abstraction. Initial layers can capture simpler and more local features, while later layers can learn more abstract and global features. 

- Increased generalization capability: can help avoid overfitting by gradually reducing the size of hidden layers. This limits the network's ability to memorize training data and encourages greater generalization to new d.

Third model: since the feature engineering work had been done previously due to the format of the available variables, in order to improve the accuracy of the network, the categorical variables are encoded using mean encoding.
