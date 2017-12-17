# Facial Recognition Using Deep Neural Network

This repository includes jupyter notebooks and test pictures of our project.
We are trying to predict the names of people in a picture provided. 
To so this, 
First we considered a well-known pre-trained Convolutional Deep Neural Networks, called VGG-FACE.  

Our Tean Members are:
* Sui Huang: sh4507@nyu.edu
* Bowen Li: bl2305@nyu.edu

## Facial Recognition Using Pre-Trained VGG-Face
In VGG-Face, the dataset has already be trained and weights can be downloaded [here](http:http://www.robots.ox.ac.uk/~vgg/software/vgg_face/src/vgg_face_matconvnet.tar.gz).

## Train Empty VGG-Face architecture using our own dataset
We created our own dataset with 73820 photos of 553 different celebrities. 
<img src="https://github.com/skylarhuang/ML_project/blob/master/owndatabase.PNG">

The size of our databset is over 185MB so you can download it from [here](https://drive.google.com/a/nyu.edu/file/d/1WQZAe42fYvGBMItPw79QOP1BdUyxGGd3/view?usp=sharing).
Use [this](https://github.com/skylarhuang/ML_project/blob/master/create_test.ipynb) file to split all photos into two set. Test set will contain 10 photos of each 553 celebrities. And the left will be kept in training set.
