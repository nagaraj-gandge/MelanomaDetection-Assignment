# MelanomaDetection-Assignment
IIIT-B UpGrad course assignment for life threatening cancer disease detection using CNN and Tensor flow and Keres  

## Table of Contents
* [General Info](#Upgrad MLAI Assignment)
* Project Pipeline
* [Technologies Used](#Python 3, TensorFlow and Keras, CNN, Augmentor)
* [Acknowledgements](#acknowledgements)

## General Information
* ### Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- This is an Upgrad AI/ML course assignment.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion
 
* ### Buisiness Objectives
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Project Pipeline
- Data Reading/Data Understanding → Defining the path for train and test images 
- Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
- Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
- Model Building & training : 
    Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~20 epochs
- Write your findings after the model fit, see if there is evidence of model overfit or underfit
- Choose an appropriate data augmentation strategy to resolve underfitting/overfitting 
**Model Building & training on the augmented data :**
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~20 epochs
  - Write your findings after the model fit, see if the earlier issue is resolved or not?
**Class distribution: **
  - Examine the current class distribution in the training dataset 
  - Which class has the least number of samples?
  - Which classes dominate the data in terms of the proportionate number of samples?
**Handling class imbalances:** 
  - Rectify class imbalances present in the training dataset with Augmentor library.
**Model Building & training on the rectified class imbalance data:**
  - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
  - Choose an appropriate optimiser and loss function for model training
  - Train the model for ~30 epochs
  
## Technologies Used
- numpy - 1.24.1
- pandas - 1.3.4
- matplotlib.pyplot - 3.5.2
- seaborn - 0.12.2
- statmodels - 0.13.5
- sklearn - 0.0.post1
- tensorflow   2.12.0
- tensorflow-datasets  4.9.2
- tensorflow-estimator    2.12.0
- tensorflow-gcs-config   2.12.0
- tensorflow-hub     0.13.0
- tensorflow-io-gcs-filesystem     0.32.0
- tensorflow-metadata    1.13.1
- tensorflow-probability  0.20.1
- tensorstore   0.1.38

## Acknowledgements
- This project was based on Upgrad AIML assignment.

## Contact
Created by Nagaraj G 
