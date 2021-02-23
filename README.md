# Detect-Pneumonia-from-X-ray-images-with-Machine-Learning-Python-

# KGMI
# ![pneumonies](https://user-images.githubusercontent.com/73962468/108904991-d38d7f80-7627-11eb-9810-766357bf429a.png)
# 

**Our Team** : Kyros George, Manolas Ioannis

URL: 
- https://www.kaggle.com/c/detect-pneumonia-fall-2020

## Description
This competition was about detecting pneumonia from chest X-Rays. The images are gray-scale with various sizes. There are 3 image classes:      

Class 0: no disease      
Class 1: bacterial pneumonia 
Class 2: viral pneumonia

# ![applsci-10-03233-g008-550](https://user-images.githubusercontent.com/73962468/108903806-67f6e280-7626-11eb-9aab-bb8de218d180.jpg)
## Specifications
The following technologies will be used to implement the requirements of the application:
- Code Language : Python
- Platform : Google Colab
- Libraries : pandas, keras, tensorflow

# ![libraries](https://user-images.githubusercontent.com/73962468/108905303-38e17080-7628-11eb-8960-65f37cce4260.png)

## Dataset
The data are split into two folders:

    Folder train_images contains 4672 train images, out of which
        1227 images belong to class 0
        2238 images belong to class 1
        1207 images belong to class 2 

    Folder test_images contains 1168 test images

The file labels_train.csv contains the class labels of the images in the form of pairs

file_name, class_id

where

    class_id = 0 if the image corresponds to a subject without disease (normal)

    class_id = 1 if the image corresponds to a patient with bacterial pneumonia

    class_id = 2 if the image corresponds to a patient with viral pneumonia

Type | Number
------ | ---------
Normal | 1227
Bacterial Pneumonia | 2238
Viral Pneumonia | 1207
Amount | 4672

## Pre-trained Models

