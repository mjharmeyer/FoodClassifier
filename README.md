# Food Image Classification Project

## Overview
Welcome to my Food Image Classification Project! This project demonstrates my skills in computer vision and deep learning using PyTorch and the Fastai library. I have developed a beginner-level image classifier that can identify whether a food image is either "Ice Cream" or "Prime Rib." This project is meant to showcase my proficiency in creating practical computer vision solutions.

## Project Objectives
The main objectives of this project are as follows:
1. Create a simplified image classification model for identifying "Ice Cream" and "Prime Rib" images.
2. Utilize a pre-trained convolutional neural network (CNN) architecture for feature extraction.
3. Fine-tune the model on a small, custom dataset containing "Ice Cream" and "Prime Rib" images.
4. Provide a user-friendly interface to upload new food images for classification.
5. Display classification results, including the predicted class and confidence scores.

## Code Walkthrough

### 1. Data Preparation
To start, I downloaded a food dataset and extracted it using Fastai's `untar_data` function. This dataset originally contained various food categories, but for this project, I focused on just "Ice Cream" and "Prime Rib" images.

### 2. Data Preprocessing
I preprocessed the data by renaming and removing images based on their class labels. This step ensured that the dataset only contained relevant images for our binary classification task.

### 3. Data Loading
I used Fastai's `ImageDataLoaders` to create data loaders for training and validation. These data loaders are crucial for feeding data into the model during training and evaluation. I also applied image transformations like resizing to ensure compatibility with the chosen CNN architecture.

### 4. Model Training
For the model architecture, I chose the popular ResNet34 pre-trained on ImageNet. I then fine-tuned this model on our custom dataset for 10 epochs. The use of a pre-trained model significantly improved model performance, even on a limited dataset.

### 5. Image Upload and Classification
I integrated a user-friendly image upload mechanism using Google Colab's file upload feature. Users can upload their own food images for classification.

### 6. Classification Results
Finally, I processed the uploaded image, made predictions, and displayed the classification results. This includes indicating whether the image is classified as "Ice Cream" or "Prime Rib" and providing confidence scores for each class.

## Limitations and Future Improvements
Obviously, this project has very limited real world implications. While there is not much of a use of having a computer only classify an image as either prime rib or ice cream, this was a project I undertook to teach myself about computer vision and the PyTorch libraries. I hope to build on this knowledge with more robust and practical projects in the future.

## Conclusion
This project highlights my skills in computer vision, PyTorch, and Fastai. I invite you to explore the code and interface, upload your own food images, and witness the model's classification capabilities. Thank you for taking the time to review this project, and I'm excited to discuss it further with you!
