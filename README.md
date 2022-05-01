# Deep Learning Homework 1 : Leaf Classification

<p align="center">
  <img width="50%" src="https://images.unsplash.com/photo-1477414348463-c0eb7f1359b6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80" alt="header" />
</p>


[![Codalab](https://img.shields.io/badge/closed-codalab-green)](https://codalab.lisn.upsaclay.fr/competitions/226)

## Overview

This repository contains the jupyter notebook used for the first homework of the Artificial Neural Networks & Deep Learning course given by Professors Matteuci and Boracchi at Politecnico di Milano. The homework took the form of an image classification competition on Codalab. We were supplied with the train and validation set. Then, we had to submit our models on the Codalab platform to evaluate them on the hidden evaluation set.

The first homework consisted in an image classification task. The dataset contains pictures of leaves belonging to 14 different species and is characterized by a strong class imbalance. In particular, tomato leaves are significantly overrepresented, as shown on the following picture :

![alt text](https://github.com/jtonglet/Deep-Learning-HW1-Leaf-Classification/blob/main/architecture.PNG?raw=true)


## CNN Model

To solve the task, we implemented a Convolutional Neural Network. The architecture of the model is shown below.

![alt text](https://github.com/jtonglet/Deep-Learning-HW1-Leaf-Classification/blob/main/architecture.PNG?raw=true)

## Results 

Our model achieves an accuracy of 94.5% on the validation set. The confusion matrix is shown below. 

![alt text](https://github.com/jtonglet/Deep-Learning-HW1-Leaf-Classification/blob/main/architecture.PNG?raw=true)
