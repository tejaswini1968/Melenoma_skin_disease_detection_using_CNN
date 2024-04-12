# Melonoma skin cancer disease detection using CNN
> Building a CNN based model ehich detects melanoma.it isa type of cancer that can deadly if not detected early.the need is to alert the dermalogists about the presence of melonoma has the potential to reduce the manual effort while diagnosis.

## Table of Contents
* [General Information](#general-information)
* [Methods Used](#methods-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

- Background:Detecting melenoma which will cause a serious cancer if not treated early which might even lead to death, accounts for 75% of skin cancer deaths.

- Bussiness problem:build a multiclass classification model using a custom convolutional neural network in TensorFlow for detecting melenoma. 

- Dataset:The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:Actinic keratosis,Basal cell carcinoma,Dermatofibroma,Melanoma,Nevus,Pigmented benign keratosis,Seborrheic keratosis,Squamous cell carcinoma,vascular lesion.

## Methods Used

- Data reading/understanding
- Importing all the important libraries
- Creating a dataset
1.   Defining some parameters for the loader
2.   creating a training dataset
3.   creating a test dataset

- Visualize the data
- Create the model 1
- Compiling the model 1
- Training the model 1-30 epochs
- visualizing the train vs validation accuracy & train vs validation loss for Model 1
- resolve overfitting
- Create the model 2
- Compiling the model 2
- Training the model 2-30 epochs 
- visualizing the train vs validation accuracy & train vs validation loss for Model 2
- Rectify the class imbalance
-distribution of augmented data after adding new images to the original training data

-Train the model on the data created using Augmentor
1.   Defining some parameters for the loader
2.   creating a training dataset
3.   creating a test dataset

- Create the final model
- visualizing the train vs validation accuracy & train vs validation loss for final Model

## Conclusions
- From model 1 we can see that there is overfitting in the model where the training accuracy is around 90% and validation accuracy which is 55% so from these we can clearly see that the model is learning too many specific details about your training set which leads to overfitting.
- In model 2 there is slight change in the accuracy when we compare with model 1 as we introduced augumentation layer and added a few dropout layers and trying to handle class imbalance.here both training and validation accuracy are similar arounf 55% but the accuracy isnt that good.
- For the final model we can see that the accuracy has increased from 55%-84%
- The final Model has training accuracy of 84% and validation accuracy of 82%.

## Technologies Used

- matplotlib - version 3.5.1
- pandas - version 1.4.2
- numpy - version 1.21.5
- plotly - version 5.6.0
- tensorflow - version 2.16.1

## Acknowledgements
Greatful to upgrad for giving a chance to work on this project.

## Contact
Created by [@tejaswini1968] - feel free to contact me!


