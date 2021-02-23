# Detect-Pneumonia-from-X-ray-images-with-Machine-Learning-Python-

# KGMI
# ![pneumonies](https://user-images.githubusercontent.com/73962468/108904991-d38d7f80-7627-11eb-9810-766357bf429a.png)

**Our Team** : Kyros George, Manolas Ioannis
- We achieved to take the 3rd Place of the MS.c's Machine Learning Competition 
# ![bathmologia](https://user-images.githubusercontent.com/73962468/108909163-e060a200-762c-11eb-8c4c-4ecac3690f33.jpg) 

- URL: https://www.kaggle.com/c/detect-pneumonia-fall-2020

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
- VGG16
# ![vgg16](https://user-images.githubusercontent.com/73962468/108906638-c7a2bd00-7629-11eb-812b-bc0e630cfc36.png)

- EfficientNetB0
# ![eff](https://user-images.githubusercontent.com/73962468/108906658-cb364400-7629-11eb-9122-6d79d7ecd4bc.png)

## Results

- We managed to achieve a score ~= 85% with Efficient and ~= 82% with VGG-16 at private leaderboard of competition on kaggle.
 
## VGG-16
# ![vgg16_acc](https://user-images.githubusercontent.com/73962468/108907755-287ec500-762b-11eb-87a5-9a283900986c.png)

## EfficientNetB0
# ![efficientnetb0_acc](https://user-images.githubusercontent.com/73962468/108907769-2d437900-762b-11eb-9c62-b928071bd0f3.png)
