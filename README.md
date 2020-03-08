# Facial Expression Detection Using Keras And Deploy With Flask

In this project, I made a custom CNN-model which can detect the ***7 universal facial expressions*** and deployed the model using ***Flask***.

The ***7 universal facial expression*** includes

* Surprise
* Happy
* Neutral
* Angry
* Sad
* Disgust
* Fear

## Sample Output

![facial](sample_out.gif)

## Dataset

I used the dataset from ***[this](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)*** Kaggle competition.

## Model Architecture

![mode](model.png)

This is the model architecture that I used for facial expression detection.

## Training

Got 67% validation accuracy within 15 epoch which took 7 min 30 sec.

For more details check [Facial_Expression_Training.ipynb](Facial_Expression_Training.ipynb).

## Deploying using Flask

To test the deployed model 

* Keep the input video in videos folder.

* run main.py.

> Python3 main.py

