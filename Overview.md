# W207 Final Project
## Brief Description
This project will aim to predict facial emotions. This stems from a Kaggle competition (https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)
## Team Members
Elise Gonzalez, Courtney Smith, Reece Koe
## Problem Statement 
The dataset provided consists of roughly 30,000 images that are labeled one of 7 emotions (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). Each image is a 48x48 pixelated image of a face. This project will require testing different machine learning techniques to find the most accurate way to predict the emotions of the images.
## Objective 
Predict the emotion of each image in the test set with 90% accuracy.
## Approach/Methodology
Try different models to find which one is most accurate 
- SVM 
- Naive Bayes
- CNN

Focus on the most accurate model approach
- Test out different combinations of layers to find ideal set of layers 
- Perform grid search on hyperparameters: batch size and # of epochs
- Train final model

## Data sets (potential)
https://www.kaggle.com/ashishpatel26/facial-expression-recognitionferchallenge/version/1

## What is considered success/failure? 
Success: Predicting the emotions of images in the test set with at least 90% accuracy

Failure: Producing a volatile model that is overfitted and cannot accurately predict emotions
## Evaluation Parameters (potential)
Accuracy 
- Num. Correct Labels / Num. Observations
- Displayed by Confusion Matrix 
