# Binary Classification Project

This project is a beginner-friendly machine learning example that uses the Wisconsin Diagnostic Breast Cancer (WDBC) dataset to build a binary classification model. The goal is to predict whether a breast tumor is likely benign or malignant based on features such as tumor size, texture, smoothness, and other cell nucleus measurements.

## What the project does

The project:

- loads a breast cancer dataset
- explores the data and its key features
- prepares the data for model training
- trains a classification model
- evaluates how well the model distinguishes between benign and malignant cases

This is a classic example of binary classification, where the model chooses between two outcomes:

- Benign
- Malignant

The dataset used here is the WDBC dataset, which contains measurements from digitized breast mass images and is widely used in machine learning and medical diagnosis examples.

## Who the project is for

This project is designed for:

- students learning machine learning and data science
- beginners who want to see how a binary classification workflow works
- anyone interested in medical data analysis in a simple, understandable example
- people exploring Jupyter Notebook-based projects

It is especially useful for learners who want a practical example of how classification models are trained and evaluated using real-world data.

## How to use it

### 1. Open the notebook

This repository contains a Jupyter Notebook named:

- `DATA_555_Project_2_Binary_Classification.ipynb`

Open it in Jupyter Notebook or JupyterLab.

### 2. Make sure the data file is available

The dataset file is included in the repository:

- `wdbc.data`
- `wdbc.names`

The notebook expects these files to be in the same folder as the notebook when it runs.

### 3. Run the notebook cells in order

Run each cell from top to bottom. The notebook typically covers:

- importing libraries
- reading the dataset
- examining the data
- splitting data into training and testing sets
- training a model
- evaluating model performance
- reviewing the results

### 4. Interpret the results

The notebook will show model accuracy and other evaluation metrics that help you understand how well the classification model performs.

## Repository contents

- `DATA_555_Project_2_Binary_Classification.ipynb` - main analysis and model-building notebook
- `wdbc.data` - dataset used for training and evaluation
- `wdbc.names` - dataset description and feature information

## Notes

This project is intended as an educational example. It demonstrates the basic workflow of data preparation, model training, and evaluation for a binary classification task.

If you are new to machine learning, this project is a good way to see how a real dataset is used in practice.
