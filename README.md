# Kinship-Classifier
This notebook is an end-to-end Deep Learning project, the goal of this project is to take two images and classify whether they have parent-child relationship or not. 

What I did in this project:
- Preprocessing the data to my need which is a pair of two people, and a label either 0 or 1, 1 if they have parent-child relationship, 0 if not.
- Converting the pair of people into pair of images
- Creating a custom Pytorch Dataset class to fit the requirement that my model takes 2 input images at a time.
- Creating two splits of the dataset, one with split based on each pair of people, and the other is based on pair of images.
- Defining Transformations and Dataloaders
- Defining two model Architectures
- Training the models
- Testing the models

I did this project while taking the Udacity Deep Learning nanodegree
