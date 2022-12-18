# Lip Reading Word Classification 

## Project Description 
Lip reading, also known as visual speech recognition, is the technique of understanding speech only through visually interpreting the movement of the lip. The goal of this project is to create a classifier model that can identify the speech content of a sequence of images of a speaker uttering a single word. The primary motivation behind this project is the existence of large volumes of videos on the internet without subtitles or captions. This project can help extract information from these videos online, benefiting hearing-impaired groups, and increasing their accessibility to video media. Our solution approach is to implement a CNN-LSTM model, which is well suited for sequence classification problems with spatial inputs, such as images and videos. Afterward, perform tuning to identify best performing hyperparameters. 

## Repository Structure
The repository contains the following files: 
- preprocessing_MIRACL_V1.ipynb: This was used to preprocessing all images in MIRACL_V1 dataset 
- training_MIRACL_V1.ipynb: Thie notebook implements a CNN-LSTM Model, and trains the model. 
- tune_MIRACLV1.ipynb: This notebook contains code for the tuning of hyperparameters. 

The MIRACL_V1 data used for this project can be downloaded from this [link](https://sites.google.com/site/achrafbenhamadou/-datasets/miracl-vc1).


## Instructions 
1. Make sure the path in the notebooks is the correct path to the directory where the data is located on. 
2. Run preprocessing_MIRACL_V1.ipynb before running the training or tuning notebooks. 

## Results

## Resources Used and Relevant Works 
