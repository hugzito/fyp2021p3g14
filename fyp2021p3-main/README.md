# First year project ITU 2021, mini-project 3


This is a repository for the course First Year Project (mini-project 3) at IT University of Copenhagen. 

This course takes place on three platofrms: Github, LearnIT and Zoom:

* In this Github repository you will find all content and technical part of the course
* LearnIT is used for announcements, general information, discussion forum
* Zoom is used for meetings 

Your lecturer is Veronika or Dr. Cheplygina.


## Project goals

In this project you will learn to measure features in images of skin lesions, and predict the diagnosis (for example, melanoma) from these features in an automatic way. 
You will likely:

* Implement methods to measure "handcrafted" features
* Predict the lesion diagnosis using simple classifiers, based on the features
* Perform experiments to test different parts of your method


## Project code

In this project you will work with Python. You can use your favorite editor. 

To start with, you get two files:

* `fyp2021p3_group00_functions.py` with functions to extract features etc.
* `fyp2021p3_group00.py` with the main script, which loads the images, calls the functions, and reproduces your results.  

If you prefer, you can use a notebook instead. 

Do not forget to replace your group number in the file names. 


# Data

You can use two types of data for the project:

* Default images, available in this repository. These images are from the ISIC 2017 challenge.
* Images from other public repositories, which you are encouraged to do.

In general, Github is not very suitable for large collections of image files, so you may need to use other solutions (such as downloading a zip archive from an external source, and unzipping it before your script runs.

## ISIC 2017 data

The ISIC 2017 dataset is available via https://challenge.isic-archive.com/landing/2017. There are more than 2000 images available in this dataset. 
In this repository, only 150 images from this dataset are added, as a demonstration. The following is available per image:

*	`ISIC_[ID].png` the image of the lesion
*	`ISIC_[ID]\_segmentation.png` the mask of the lesion, showing which pixels belong to the lesion or not
* The label of the image, i.e. whether it belongs to the Melanoma class (0 = no, 1 = yes), and/or the Keratosis class (0 = no, 1 = yes). 


## Other data

You are also encouraged to use other publicly available data, for example ISIC challenges from other years. See for example Kaggle grand-challenge.org .



# Exercises

During the exercises you will become more familiar with processing images, measuring features, applying simple classifiers, and asking research questions about the above. 
These exercises will help you in completing your project.   


# Final project

Similar to the other projects, you need to hand in a report and your code (via Github, more details TBA). 
