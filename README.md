# Facial-Keypint-Detection
This is a repository of my project facial keypoints detection. This is the first project of my Computer Vision  Nanodegree


## Introduction:
- Facial Key Points (FKPs) detection is an important and
challenging problem in the field of computer vision, which
involves detecting FKPs like centers and corners of eyes,
nose tip, etc. The problem is to predict the (x, y) realvalued co-ordinates in the space of image pixels of the FKPs
for a given face image. It finds its application in tracking
faces in images and videos, analysis of facial expressions,
detection of dysmorphic facial signs for medical diagnosis,
face recognition, etc.

##  Motivation/Purpose: 
- Main Purpose of this project is to detect facial keypoint from a given image dataset. So first we define the CNN Architecture for this 
### CNN Architecture
- Convolutional layers
- Maxpooling layers
- Fully-connected layers
in model.py file
Then We detect the face using Haar Cascade classifier after detecting frontial faces we pass these detected faces to trained model

##  How to Use 
- Go through instruction 


- Change the number of convolutional layers and see what happens.
- Increase the size of convolutional kernels for larger images.
- Change loss/optimization functions to see how our model responds. 
- Add layers to prevent overfitting.
- Change the batch_size of your data loader to see how larger batch sizes can affect our training.
.
## Developer 
  diksha  
  - [Github](https://github.com/diksha0799) 
  - [linkedin](https://www.linkedin.com/in/diksha-ab16b6165/)


