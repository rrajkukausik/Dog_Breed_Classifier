# UDACITY DEEP LEARNING NANODEGREE 

## DOG BREED CLASSIFIER

**Table Of Contents**

```
1. Project Motivation
3. File Structure
4. File Description
5. How to Download the dataset
6. Acknowledgement
7. About the Author
```

The project is supported by Python 3.x (Hint: directly install the Anaconda distribution), libraries and packages:


```
  1. Numpy
  2. glob
  3. opencv 
  4. matplotlib
  5. tqdm
  6. torch
  7. torchvision
  8. PIL
```


## Project Motivation

This project aims at classifying the Dog Breed based on images given to it and it uses a pre-trained VGG16 Net to find the predicted class for a given image.

You can get all the project specification from the given link.

[LINK](https://review.udacity.com/#!/rubrics/2259/view)


## Project Overview

In this project, i have build a pipeline to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human face, the code will identify the resembling dog breed.


## File Structure

```
├── README.md
├── dog_app.ipynb
├── data
   ├── dog_images/
   ├── iwf/
├── harcascade/
   ├──  harcascade_frontalface_alt.xml
├── images/
   ├── various images required in the dog_app.ipynb file
├── report.html
```

## How to Download the Dataset

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
2. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

## Acknowledge
  Besides, you must know that the project is under the Udacity Deep Learning Nanodegree.

## About the Author
* **Raj Kumar Kausik**
* **Email-** - rrajkukausik@gmail.com



