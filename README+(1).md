# Melanoma Assignment
**Problem statement:** 

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
### Background of the project

 Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. The objective of the project is to build a CNN based model which can accurately detect melanoma.  
 
### Background of dataset

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

### Business Objective of the project
To build a CNN based model which can accurately detect melanoma.A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
1. Model1 is the simple CNN based architecture trained for 20 epoch using the raw dataset to classify the images.
2. Model1 shows Overfitting issue.
3. To overcome by overfitting problem we used data augmentation strategy and built Model2.
4. Model2 is not showing much imrovement. Model2 also shows the overfitting problem.
5. Used Augmentor library to rectify the imbalance of samples over each class.
6. Built the Model3 using newly created dataset.
7. The accuracy of the Model3 is improved after using the Augmentor library and rectifying the imbalance of samples of each class.
8. Model3 shows 83.03% accuracy of training and 78.40% of accuracy of validation data set, but it is not enough.
9. Model4 is built by adding Dropout layer to the Convolution unit of Model3 architecture each, no much improvemnet in accuracy.
10. Model5 is built using the new dataset by adding some more augmented data. There is no much improvement in accuracy.

# Future Enhancement

1. We can add more data by considering the suitable data augmentation operation and build the model using new dataset.
2. We can improve the model by adding more convolution layers to the network.

## Technologies Used
- tensorflow 2.11. 0
- keras 2.11.0.
- Augmentor 2.0.9
- matplotlib 3.0

## Acknowledgements
Thanks for Upgrad to give this assignment to learn. This is very inspiring assigment to learn many tools and techniques to build the CNN based model for multi class classification.

## Contact
Created by Prathima Kumari B V
Developed as part of the Exloratory Data Analysis Module required for Advanced Certificate Program for ML and AI - IIIT,Bangalore.

