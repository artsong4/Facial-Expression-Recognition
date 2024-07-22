# Facial Expression Recognition for Sentiment Analysis

This repository contains the project for facial expression recognition aimed at performing sentiment analysis. The project leverages data preprocessing, exploratory data analysis (EDA), and machine learning models to identify and classify facial expressions into different sentiment categories. Contributors: Derek Dolan, David Mansoir, Hans Broders, Yesul Song

## Table of Contents
1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Skills Demonstrated](#skills-demonstrated)
4. [Dataset](#dataset)
5. [Analysis](#analysis)
    - [Data Preprocessing](#data-preprocessing)
    - [Exploratory Data Analysis](#exploratory-data-analysis)
    - [Modeling](#modeling)
    - [Evaluation](#evaluation)
6. [Repository Structure](#repository-structure)

## Project Overview
This project aims to recognize facial expressions to perform sentiment analysis using convolutional neural networks (CNN). It uses data augmentation, model checkpoints, and early stopping to enhance model performance.

## Objectives
- Analyze facial expression data to identify key sentiment categories.
- Develop and train machine learning models to classify facial expressions.
- Evaluate model performance and propose potential applications.

## Skills Demonstrated
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning: CNN, Data Augmentation
- Model Evaluation
- Data Visualization

## Dataset
We resized all images to 240x240 pixels to ensure uniformity. The dataset was then randomized and split into training, validation, and test sets to ensure a balanced distribution of early and late frames in all sets. Data augmentation techniques such as rotation and flipping were applied to enhance the model's robustness.

## Analysis
### Data Preprocessing
- **Randomization and Splitting**: Data was randomized and split into training, validation, and test sets using `Data_Splitting.ipynb`.
- **Image Augmentation**: Applied augmentations such as rotation and flipping to the training set to enhance model robustness.

### Exploratory Data Analysis
- **Data Visualization**: Visualized the distribution of each facial expression category and key features to understand patterns within the dataset.

### Modeling
- **Model Architecture**: Built and trained Convolutional Neural Network (CNN) models with data augmentation.
- **Callbacks**: Implemented early stopping and model checkpoints to prevent overfitting and save the best performing models.

### Evaluation
- **Performance Metrics**: Evaluated model performance on the test set, achieving high accuracy and low validation loss, demonstrating the model's effectiveness in classifying facial expressions.


## Repository Structure
```plaintext
Facial-Expression-Recognition/
├── data/
│   └── face-sentiment-data-metadata.json
├── Facial_Expression_Recognition.ipynb
├── Data_Splitting.ipynb
├── Facial_Expression_Model.h5
├── Project_Presentation.pptx
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
