# gender_prediction
Gender prediction from Indian names
Given a name of person, the trained model tries to predict the gender of the person. The model has been trained only with Indian names for now.


The data has been collectted from the following sites: 

parenting.firstcry.com
www.indianmirror.com

Model description:
Charecter level embedding(One hot embeddding) has been used and has been fed to a sequential Recurrent Neural Network(bidirectional).
Currently the model is tranied for names with maximum 20 charecters.

I am currently trying to train the model for more than 20 charecters. Also, it will be fun to analyze the patters for recurrent neural networks with a focus on understanding these hidden state dynamics



Libraries used:
1. TensorFlow
2. Pandas
3. Numpy
4. Sklearn