# kNN (k-Nearest Neighbor) image classifier

This repository contains the code to implement the kNN image classifier on the CIFAR-10 dataset. It which consists of following stages:

  1. During training, the classifier takes the training data and simply remembers it   
  2. During testing, kNN classifies every test image by comparing to all training images and transfering the labels of the k most similar training examples
  3. The value of k is then cross-validated.
