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
* [LipNet: End-to-End Sentence-level Lipreading](https://arxiv.org/abs/1611.01599)
* [Implementation of LipNet](https://github.com/rizkiarm/LipNet)
* [Lip Reading Word Classification](https://www.semanticscholar.org/paper/Lip-Reading-Word-Classification-Guti%C3%A9rrez-University/d3047c6191f4f771f5c02a97b6c5abbc4aaa72c2)
* [Blog Post about CNN-LSTM Networks](https://machinelearningmastery.com/cnn-long-short-term-memory-networks/)
* [Lip Reading by CNN and LSTM Architecture](https://github.com/ljw20155136/Lip-reading-by-CNN-and-LSTM-architecture)
* [Visual Speech Recognition of Lips Images Using Convolutional Neural Network in VGG-M Model](https://www.semanticscholar.org/paper/Visual-Speech-Recognition-of-Lips-Images-Using-in-Chan-Lau/66fe079106dfa5d6e3bd5a7871622e2e4561fef3)
* [Lip2Word](https://github.com/khazit/Lip2Word)
* [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf)
* [Kaggle Lip Reading Image](https://www.kaggle.com/datasets/apoorvwatsky/miraclvc1)

