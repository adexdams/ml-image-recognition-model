# ml-image-recognition-model
This is an ML Project that uses TensorFlow image recognition model to classify unstructured datasets of dogs into breeds.

## **Context**
This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and Tensorflow Hub.

### 1. Problem

To identify the breed of 120 dogs given the images provided.

For example, When a user takes a picture of  a dog in the real world and wants to determine its breed the model can do that.

### 2. Data

The data is sourced from a Kaggle dog breed identification competition: https://www.kaggle.com/competitions/dog-breed-identification/data

### 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.
www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

### 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so we should use deep learning/ transfer learning.
* There are 120 breeds of dogs (120 different classes).
* There are around 10,000+ images in the training set (these images have labels).
* There are around 10,000+ images in the test set (these images have no labels because we'll want to predict them).
