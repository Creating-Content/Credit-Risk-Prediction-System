# Credit Risk Prediction System

## Overview
The Credit Risk Prediction System is designed to help financial institutions predict whether a customer represents a good or bad credit risk. It utilizes machine learning techniques to analyze customer data and make predictions based on various features.

## Dataset
The dataset used for training and testing the Credit Risk Prediction System consists of 21 features related to customers' financial information. It is used to predict whether a customer is creditworthy or not.

Dataset Source: [Credit Risk Dataset](https://drive.google.com/file/d/19VXoOs3sWJZVIZ8JpFcnChrhlJbRWjKR/view?usp=share_link)

### Sample Dataset:

| Feature 1 | Feature 2 | ... | Feature 21 | Class |
|------------|------------|-----|------------|-------|
| Value      | Value      | ... | Value      | Good  |
| Value      | Value      | ... | Value      | Bad   |
| Value      | Value      | ... | Value      | Good  |



## System Design

          +----------------------------------+
          |            Read Dataset          |
          +----------------------------------+
                     |
                     v
          +----------------------------------+
          |       Handle Null Values         |
          +----------------------------------+
                     |
                     v
          +----------------------------------+
          |       Data Preprocessing         |
          |       - Handling duplicates      |
          |       - Label Encoding           |
          +----------------------------------+
                     |
                     v
          +----------------------------------+
          |   Split Data into Training       |
          |       and Test Sets              |
          +----------------------------------+
                     |
                     v
          +----------------------------------+
          |     Model Training and Testing   |
          |  (Logistic Regression, KNN,      |
          |   SVM with linear and rbf kernel)|
          +----------------------------------+
                     |
                     v
          +----------------------------------+
          |     Evaluate Model Performance   |
          +----------------------------------+



## Model Conclusion
"In conclusion, after evaluating the performance of various classification models, we found that the SVM Classifier with linear achieved the highest accuracy. Therefore, we recommend using this model for credit risk prediction."

## Project Structure
- `README.md`: This file, providing an overview of the project.
- `Minor Project - Al Saim Shakeel.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `requirements.txt`: Text file listing the dependencies required to run the code.
- `credit_customers (1).csv`: Dataset used in the project.
- `data.csv`: Dataset after applying encoding techniques.
- `Minor Project - Jupyter Notebook.pdf`: PDF containing the code for data preprocessing, model training, and evaluation.

## Installation
### Install the required modules:
- pandas
- scikit-learn
- matplotlib
- numpy

## References
- [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [pandas Documentation](https://pandas.pydata.org/docs/)

# THE END