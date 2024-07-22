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
The dataset metadata is contained in `data/face-sentiment-data-metadata.json`. The images are categorized into five expressions: Agony, Happy, Neutral, Sad, and Scared.

## Analysis
### Data Preprocessing
- Randomized and split data into training, validation, and test sets using `Data_Splitting.ipynb`.
- Applied image augmentations to the training set.

### Exploratory Data Analysis
- Visualized data distributions and key features.

### Modeling
- Built and trained CNN models with data augmentation.
- Used callbacks like early stopping and model checkpoints.

### Evaluation
- Evaluated model performance on the test set.
- Achieved high accuracy and low validation loss.

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
