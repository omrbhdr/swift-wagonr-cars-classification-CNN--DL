# swift-wagonr-cars-classification-CNN--DL

.................libs...............................

              import os
              import numpy as np
              import matplotlib.pyplot as plt
              from matplotlib.pyplot import imshow
              import  pandas as pd
              import cv2
              from PIL import Image
              from tensorflow import keras
              from keras import layers as tfl
              from keras import layers, models, optimizers
              from keras.preprocessing.image import ImageDataGenerator
              from tensorflow.keras import Sequential
              from tensorflow.keras.layers import Conv2D,MaxPool2D,Dropout,Flatten,Dense,BatchNormalization
              
........................................................


Difference between Swift &amp; Wagonr Models detect with ML
About Dataset
Context
Data science beginners start with curated set of data, but it's a well known fact that in a real Data Science Project, major time is spent on collecting, cleaning and organizing data . Also domain expertise is considered as important aspect of creating good ML models.
Being an automobile enthusiast, I tool up this challenge to collect images of two of the popular car models from a used car website, where users upload the images of the car they want to sell and then train a Deep Neural Network to identify model of a car from car images.
In my search for images I found that approximately 10 percent of the cars pictures did not represent the intended car correctly and those pictures have to be deleted from final data.

Content
There are 4000 images of two of the popular cars (Swift and Wagonr) in India of make Maruti Suzuki with 2000 pictures belonging to each model.
The data is divided into training set with 2400 images , validation set with 800 images and test set with 800 images. The data was randomized before splitting into training, test and validation set.

The starter kernal is provided for keras with CNN. I have also created github project documenting advanced techniques in pytorch and keras for image classification like data augmentation, dropout, batch normalization and transfer learning

Inspiration
With small dataset like this, how much accuracy can we achieve and whether more data is always better. The baseline model trained in Keras achieves 88% accuracy on validation set, can we achieve even better performance and by how much.

Is the data collected for the two car models representative of all possible car from all over country or there is sample bias .

I would also like someone to extend the concept to build a use case so that if user uploads an incorrect car picture of car , the ML model could automatically flag it. For example user uploading incorrect model or an image which is not a car
![image](https://github.com/omrbhdr/swift-wagonr-cars-classification-CNN--DL/assets/12261537/387b735b-a76a-4ab5-83a1-7b7a20b65fff)
![image](https://github.com/omrbhdr/swift-wagonr-cars-classification-CNN--DL/assets/12261537/fac5db03-31e7-4db8-ab56-97fd896066e0)
