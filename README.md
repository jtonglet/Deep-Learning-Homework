# Artificial Neural Networks and Deep Learning homeworks

This repository contains the jupyter notebook used for the two homeworks of the Artificial Neural Networks & Deep Learning course given by Professors Matteuci and Boracchi at Politecnico di Milano. 

## Homework 1 : Leaf Classification   🍂🍃🍁🌿

[![Codalab](https://img.shields.io/badge/closed-codalab-green)](https://codalab.lisn.upsaclay.fr/competitions/226)

### Overview

The first homework took the form of an image classification competition on Codalab. We were supplied with the train and validation set. Then, we had to submit our models on the Codalab platform to evaluate them on the hidden test set.
The dataset contains pictures of leaves belonging to 14 different species and is characterized by a strong class imbalance. In particular, tomato leaves are significantly overrepresented, as shown on the following picture :

![distribution](https://github.com/jtonglet/Deep-Learning-HW1-Leaf-Classification/blob/main/img/distribution.PNG?raw=true)



## Homework 2 : Forecasting   🔮🧙‍♂️⏳


[![Codalab](https://img.shields.io/badge/closed-codalab-green)](https://codalab.lisn.upsaclay.fr/competitions/621)

### Overview

The second homework consisted in a multivariate time series forecasting task. The dataset includes 7 time series. The goal was to design and implement forecasting models to learn how to exploit past observations in the input sequence to correctly predict the next 864 time steps.
Predictions were evaluated with the RMSE on a hidden test set. 
By using the N-BEATS model we achieved a final RMSE score of 3.79.

The forecast for the first tree time series are shown below :

![forecast values](https://github.com/jtonglet/Deep-Learning-HW1-Leaf-Classification/blob/main/img/forecast.png?raw=true)


 ### Reference 
 
 Oreshkin, B. N., Carpov, D., Chapados, N., & Bengio, Y. (2019). N-BEATS: Neural basis expansion analysis for interpretable time series forecasting.
