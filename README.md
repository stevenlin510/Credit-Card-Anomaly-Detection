# Credit-Card-Anomaly-Detection

#### Introduction
We use four different methods to complish this task. 

#### Methods
1. Normal 
  We don't preprocess the data and feed it into neural network directly.

2. Undersample
  In order to sole the unbalance data issue, we undersample the normal ones to make our model reduce the false positives. 

3. RNN
  Because credit card transactions are squence data, we implement basic RNN model to fit the all data.
  
4. GANanomaly
  This code is based on [GANomaly](https://github.com/samet-akcay/ganomaly).
  
#### Dataset 
https://www.kaggle.com/mlg-ulb/creditcardfraud

