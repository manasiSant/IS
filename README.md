# IS_Project
Intelligent Systems project on 'Entity relationship extraction using neural embedding approach'
This a project made as part of course Intelligent Systems.

Project title : Entity relationship extraction using neural embedding approach

Dataset
We have used subset of people/person section of freebase for training and testing our model. 
Information of each person such as place of birth, gender, siblings, parents, profession, notable types, ethnicity , religion , sports associated etc.


Implementation
We have used Theano library of python for modelling of neural network . 
70 percent of the Dataset has been used for training and rest for testing part. All the parameters of the model are updated using mini batch stochastic gradient descent with appropriate learning rate for different relations.
The number of tensor slices of the relation parameter we have were set to 4. The number of corrupted triples for every training triple are set to 10 . The number of mini batches are set to 10 . 
The number of training epochs are set to 20.The regularisation parameter is set to 0.0001.
