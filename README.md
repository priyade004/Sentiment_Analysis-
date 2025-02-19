# README: GPU-Accelerated LSTM, GRU, and BiLSTM with TF-IDF

## Overview
This project focuses on sentiment analysis using deep learning techniques such as LSTM, GRU, and Bidirectional LSTM. The workflow includes data preprocessing, feature extraction using TF-IDF, and model training on a GPU.

## Workflow

### 1. Reading the Dataset
- Load the dataset from a CSV file.

### 2. Data Cleaning & Preprocessing
- Remove columns containing irrelevant values.
- Perform necessary data preprocessing steps.

### 3. Labeling
- Assign sentiment labels (Positive, Negative, Neutral).

### 4. Exploratory Data Analysis
- Generate count plots to visualize sentiment distribution.

### 5. TF-IDF Feature Extraction
- Convert text data into numerical features using TF-IDF.
- Save the sparse matrix representation.

### 6. Data Splitting
- Split the dataset into training and testing sets.

### 7. Undersampling using Edited Nearest Neighbors (ENN)
- Balance the dataset by applying ENN undersampling.

### 8. Data Reshaping
- Reshape data for deep learning model compatibility.

### 9. Model Training
- Train different deep learning models:
  - LSTM
  - GRU
  - Bidirectional LSTM
- Concatenate relevant features where necessary.

### 10. Model Saving
- Save trained models for later use.

## Requirements
- Python (recommended: 3.7+)
- TensorFlow / Keras
- Scikit-learn
- Pandas
- Matplotlib / Seaborn

## Usage
1. Run the Jupyter Notebook to preprocess data and train models.
2. Evaluate model performance on the test set.
3. Deploy the trained model for sentiment analysis.

## License
This project is open-source and available for modification and distribution.

