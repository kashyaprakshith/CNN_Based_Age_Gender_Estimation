# CNN_Based_Age_Gender_Estimation
This is an Implementation of Age and Gender Estimation using CNN
## Overview
The basic goal of the project was to predict the age and gender of a person, given his/her facial image using Convolutional Neural Network. Both the models were trained on top of Keras API (which is in turn built on top of Tensorflow) and finally deployed in Flask.

This project includes 2 seperate tasks -

Age & Gender Classification - This model classifies ages into 5 categories: 0-24, 25-49, 50-74, 75-99, 100-124 and gender into 2 categories: male, female. The model was trained on UTKFace dataset (23,708 images) and attained a validation accuracy of 0.8279 and 0.9502 on age and gender classification respectively.

Age Estimation - This was a regression task. The model was trained on WIKIFace dataset (34,200 images). The model attained a validation mae of 6.55 (the average magnitude of error in predicting the exact age)

# Please check Age Estimation.ipynb for detailed analysis about age estimation
# Please Check Gender & Age Classifier.ipynb for detailed analysis about gender classification
