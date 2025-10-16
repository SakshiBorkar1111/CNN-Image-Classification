# Cat vs Dog Image Classification (CNN)



## Overview: 
A Convolutional Neural Network (CNN) model built using TensorFlow & Keras to classify images as Cat or Dog.

It’s a binary image classification project aimed at achieving high accuracy on unseen data.


## Business Objective:
 
Classify images of cats and dogs and predict future unseen images with maximum accuracy.

## Dataset:
 
•	Download the Cats vs Dogs dataset from [Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)

•	Two folders: cats/ and dogs/ under training_set/ and test_set/.

•	Images resized to 64×64 and normalized using ImageDataGenerator.



## Data Preprocessing: 

Images were resized, normalized, and augmented for better model performance.

## Model Architecture:

 1.	Conv2D + ReLU → Feature extraction
   
2.	MaxPooling2D → Downsampling
   
3.	Flatten → Vector conversion
	
4.	Dense (128, ReLU) → Hidden layer
	
5.	Dense (1, Sigmoid) → Output (Cat/Dog)

   

## Results:

 
-	Successfully classifies cat and dog images with good accuracy.
  
-	Generalization improved through data augmentation techniques.



