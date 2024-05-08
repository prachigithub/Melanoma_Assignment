# Project Name
> Melanoma Detection


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
 Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis
 

Data Description:

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases classes:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


Business Goal:

Build a CNN model that can help detect malanoma


Downloads
Please find the dataset link [here] train.csv

## Technologies Used
- python 3.11.7
- jupyter notebook
- pathlib 1.0.1
- tensorflow 2.16.1
- matplotlib 3.8.0
- keras 3.3.2



## Conclusions
- Training accuracy is 89 and validation accuracy is 72. Model is still overfit. We can have more regularization parameters, dropouts etc
- May be more number of layers with regularization will increase training accuracy and validation accuracy
- Accuracy on test data is 37 which is extremely low and loss is 3.73.
- Low accuracy can be attributed to less number of images making difficulat to build a efficent model.
- May be if we increase number of layers and more dropouts with batch normalization could have generated efficent model.

																																		

## Contact
Created by [prachigithub](https://github.com/prachigithub/) - feel free to contact me!