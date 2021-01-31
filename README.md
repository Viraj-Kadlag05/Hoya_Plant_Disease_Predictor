# Hoya_Plant_Disease_Predictor
Patravaidyam - diagnosis of plant leaf disease.

## Goal:
The main goal is to use predicted status of the plant i.e whether it is healthy or diseased to prescribe remedy of the specific leaf disease.

## Prerequisites:
1. Google Colab
2. Plant Disease Dataset
3. Python 
4. Javascript
5. CSS
6. Html

## Libraries:
1. Tensorflow
2. Keras
3. Numpy
4. Matplotlib

## How the model works:
The user needs to insert input leaf image into the web application,using the _Upload Image_ button and then the input image is sent to the classification model here we have used **MobileNet** architecture and the training is performed on train and valid dataset(fetched from _kaggle_), followed by testing and the predicted output is sent back to the web application, where we get the type of plant of input leaf image and followed by its health status and the remedy button gives you the prescription of the specific disease.

<p align="center">
  <img width="800" height="1000" src="https://github.com/Viraj-Kadlag05/Hoya_Plant_Disease_Predictor/blob/main/Working%20flowchart-patravaidhyam-leaf%20detection.jpg">
</p>

## Challenges:

The dataset was very large it contained neary 70,000 samples due to which the model was taking too much for training. So we decided to reduce the samples and we took 4000 samples.


## Achivements:
collabrative Work done using **Google Collab**, large dataset stored in **Google Drive** saving system storage and increasing accessibilty.
We have successfully completed the training for our with nearly 79% accuracy. We have also developed a web interface for our project.

## What's Next:

We will try to increase the accuracy and also try to improve the web interface.Provide translation of remedies in regional language to improve reach rural audience.

