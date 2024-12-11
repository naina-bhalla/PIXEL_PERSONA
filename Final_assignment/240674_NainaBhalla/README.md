# PIXEL PERSONA Final Project
The model identifies faces in an image use Haar Cascades and then classifies the faces into either male or female.

## Overview
### Dataset
It uses a dataset with 900 images in the training dataset and 100 each in the testing and the validation set. each of the sets have 50% male images and 50% female images.

Since the dataset that I had used had no labels with the images, just were in separate labelled folders, I added labels to them when I created DataFrames for the dataset.

I preprocessed the dataset images according to the model and encoded the labels using LabelEncoder

### Model Architecture
The model itself is composed of various layers including Conv2D,MaxPooling,BatchNormalization and Dropout. It also uses early stopping callbacks to prevent overfitting.

![alt text]()

## Performance
The model gives 81.00% accuracy on the testing data and a loss of 0.377.

## Output Images


 ![alt text](Final_assignment/240674_NainaBhalla/Output_Images/sample_output_with_multiple_faces.png)

 ![alt text](Final_assignment/240674_NainaBhalla/Output_Images/output.png)
