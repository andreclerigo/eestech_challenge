# EESTech Challenge Aveiro 2022

<br>

# Description
## Hackathon 2022
## EESTEC - Electrical Engineering STudents’ European assoCiation
## Dataset: subset of CIFAR-10 dataset
The dataset consists of 40.000 images for training divided into 8 categories. The test batch contains exactly 1000 randomly-selected images from each class.

Here are the classes in the dataset:
- airplane
- automobile
- bird
- cat
- dog
- horse
- ship
- truck

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

Reference to the initial dataset: The CIFAR-10 dataset.

Within this task, you are advised to use python. Python packages that may be useful are: NumPy, Scikit−learn, Matplotlib, Pandas, TensorFlow, PyTorch.

## Programming:
For the programming part, you can turn to StackOverflow if you bump into some kind of bug or problem, but again we strongly advise against copying code for these simple tasks.
Implement your approach using a Jupyter Notebook, with sufficient but not redundant comments.

<br>

# Evaluation
## Goal
The goal in this competition is to take an image of the CIFAR-10 dataset, and determine what that digit is. For every in the test set, you should predict the correct label.

## Metric
This competition is evaluated on the categorization accuracy of your predictions (the percentage of images you get correct).

## Submission File Format
The file should contain a header and have the following format:

```
id,classid
aeroplane_s_000002.png,0
aeroplane_s_000040.png,0
etc.
```

<br>

# Data
Within this section you will find all the necessary data to train your model. More specificaly, you will find within the dataset folder all images divided into 8 classes.

Moreover, within the testset folder you will find the images on which you need to predict their label.

## Folders
- dataset - The folder that contains all images to train the model
- testset - The folder that contains all images to test the model

## Files
- sample.csv - a sample submission file in the correct format
- test_files.txt - a txt file that contains all image filenames to be used to test the model prediction performance

## Columns
- id - definition of image name
- category - class
