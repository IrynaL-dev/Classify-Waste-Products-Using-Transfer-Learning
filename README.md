# Classify-Waste-Products-Using-Transfer-Learning
EcoClean currently lacks an efficient and scalable method to automate the waste sorting process. The manual sorting of waste is not only labor-intensive but also prone to errors, leading to contamination of recyclable materials.The goal of this project is to leverage machine learning and computer vision to automate the classification of waste products, improving efficiency and reducing contamination rates. Will use transfer learning with a pre-trained VGG16 model to classify images.
Classify Waste Products Using Transfer Learning
Introduction
Project Overview
Aim of the Project
Objectives
Tasks List
Sample Task: Sample screenshot showing code and output
Setup
Installing Required Libraries
Importing Required Libraries
Task 1: Print the version of tensorflow
Background
Create a model for distinguishing recyclable and organic waste images
Dataset
Importing Data
Define configuration options
Loading Images using ImageGeneratorClass
ImageDataGenerators
Task 2: Create a test_generator using the test_datagen object
Task 3: Print the length of the train_generator
Pre-trained Models
VGG-16
Task 4: Print the summary of the model
Task 5: Compile the model
Fit and train the model
Plot loss curves for training and validation sets (extract_feat_model)
Task 6: Plot accuracy curves for training and validation sets (extract_feat_model)
Fine-Tuning model
Task 7: Plot loss curves for training and validation sets (fine tune model)
Task 8: Plot accuracy curves for training and validation sets (fine tune model)
Evaluate both models on test data
Task 9: Plot a test image using Extract Features Model (index_to_plot = 1)
Task 10: Plot a test image using Fine-Tuned Model (index_to_plot = 1)
