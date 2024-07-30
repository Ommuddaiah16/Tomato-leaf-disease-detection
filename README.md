# Tomato Leaf Disease Detection

## Overview

This project focuses on detecting various diseases in tomato leaves using Convolutional Neural Networks (CNNs). We utilize two powerful CNN architectures, **InceptionV3** and **VGG16**, to classify tomato leaf images into different disease categories. The aim is to develop an accurate model to assist in the early detection and management of tomato leaf diseases.

## Dataset

The dataset used in this project contains images of tomato leaves with the following diseases:

1. **Tomato Mosaic Virus**
2. **Target Spot**
3. **Bacterial Spot**
4. **Tomato Yellow Leaf Curl Virus**
5. **Late Blight**
6. **Leaf Mold**
7. **Early Blight**
8. **Spider Mites Two-Spotted Spider Mite**
9. **Tomato Healthy**
10. **Septoria Leaf Spot**

The dataset can be found on Kaggle as [Tomato Leaf Disease Detection](https://www.kaggle.com/datasets).

## Project Steps

1. **Data Preparation:**
   - **Dataset Download and Structure**: Downloaded the dataset from Kaggle and organized it into training, validation, and test directories.
   - **Data Augmentation**: Applied data augmentation techniques to increase the variety of training data and improve model generalization.

2. **Model Building:**
   - **InceptionV3 Model**: Implemented the InceptionV3 architecture with pre-trained weights and adapted it for the specific task of tomato leaf disease classification.
   - **VGG16 Model**: Implemented the VGG16 architecture with pre-trained weights and adapted it for the classification task.

3. **Model Training:**
   - **Training the Models**: Trained both InceptionV3 and VGG16 models using the prepared dataset. Applied appropriate callbacks such as EarlyStopping to prevent overfitting.
   - **Hyperparameter Tuning**: Adjusted hyperparameters like learning rate, batch size, and number of epochs to optimize model performance.

4. **Model Evaluation:**
   - **Validation and Testing**: Evaluated the models on validation and test datasets to assess their performance. Generated metrics such as accuracy, loss, and confusion matrices.

5. **Results and Comparison:**
   - **Model Comparison**: Compared the performance of InceptionV3 and VGG16 models to determine which architecture performs better for the task.
   - **Visualization**: Visualized the results and confusion matrices to understand model performance across different disease categories.

The dataset can be found on Kaggle as Tomato Leaf Disease Detection.

