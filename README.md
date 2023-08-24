## Estimating-ShearModulus-elastography-images
This repository contains the code and documentation for my project on estimating the shear modulus from elastography images. 
I developed this project as part of my Master's degree, and I collected the dataset used for experimentation.

# Introduction

In this project, I focused on estimating the shear modulus from elastography images, using the Scanning Laser Doppler Vibrometry (SLDV). 
Elastography is a technique that measures tissue stiffness, which can have important medical applications. 
This repository contains the implementation and documentation of the methods and algorithms I used to achieve this estimation.

# Dataset

The dataset used in this project was collected during my Master's degree studies. 
It includes a variety of SLDV images that are crucial for training and evaluating the model.
Open datasets of SLDV images were not present in accessible databases, so the proposed CNN architecture was pre-trained using synthetic wave data generated using a computational model and then fine-tuned with physical data. 
Due to privacy and copyright concerns, the dataset cannot be shared openly in this repository. 
However, I provide instructions on how to obtain a similar dataset for research purposes.

# Results

The classification of the shear modulus of the materials was performed on two separate tasks: binary classification and a five-class classification. 
During the two experiments using physical data, the binary classification achieved an accuracy of 84.4%, and the multi-class classification reported an accuracy of 76.6%. 



