# Pneumonia Classification using Chest X-Ray Images

## Project Overview
The Pneumonia Classification project aims to develop a deep learning model that can accurately classify chest X-ray images into two categories: normal and pneumonia. The project utilizes data on chest X-ray images collected from various sources to train a convolutional neural network (CNN) model.

## Objective & Business Scope
The objective of this project is to develop a deep learning model that can accurately classify chest X-ray images into normal and pneumonia categories. The model will be beneficial for healthcare professionals to aid in the diagnosis of pneumonia and improve patient outcomes.

## Benefits for Users
- Provides accurate classification of chest X-ray images.
- Aids healthcare professionals in the diagnosis of pneumonia.
- Improves patient outcomes and reduces the risk of misdiagnosis.

## Narrative of Key Steps
1. Data collection and preprocessing
2. Exploratory data analysis
3. Model development and training
4. Model evaluation and optimization

The project started with data collection and preprocessing, where data on chest X-ray images from various sources was collected and cleaned to remove inconsistencies and errors. Exploratory data analysis was performed to gain insights into the data and identify patterns and trends.

A CNN model was developed and trained on the data to classify chest X-ray images into normal and pneumonia categories. Model evaluation and optimization were performed to improve the model's accuracy and generalization performance.

The model's performance was evaluated using various metrics, including accuracy, precision, recall, and F1 score. Finally, the best-performing model was selected and deployed to a web application to enable users to upload chest X-ray images and receive predictions on whether the images show normal or pneumonia results.

The web application was built using Flask, a Python web framework, and deployed on Heroku, making it accessible to the public. The project documentation includes a detailed description of the data sources, data preprocessing steps, model development and training, model evaluation and optimization, and the web application deployment process.

##Results
Loss on test set:  0.905697194154084
Accuracy on test set:  0.8269230769230769
Recall of the model is 0.98
Precision of the model is 0.79
