# EDP-AI-ML-Week3

## Week 3: Text Preprocessing, TF-IDF and Naive Bayes Spam Classification

### Project Description

This project is part of the EDP AI & ML Week 3 assignment.

The objective of this project is to build a machine learning model that classifies SMS messages as either **Spam** or **Ham (legitimate message)**.

The project uses text preprocessing, TF-IDF vectorization, train/test splitting, and a Multinomial Naive Bayes classifier.

---

## Dataset

- Dataset Name: SMS Spam Collection
- Original File Name: `SMSSpamCollection`
- Converted File: `spam_dataset.csv`
- Cleaned File: `cleaned_spam_dataset.csv`
- Number of Messages: 5,572
- Labels:
  - `ham` - legitimate/non-spam message
  - `spam` - unwanted or spam message

### Dataset Columns

| Column | Description |
|---|---|
| `label` | Class of the SMS message: ham or spam |
| `message` | Text content of the SMS |

---

## Objectives

- Load the SMS spam dataset using Pandas.
- Explore the dataset.
- Check for missing values.
- Perform basic text preprocessing.
- Split the dataset into training and testing data.
- Convert text into numerical features using TF-IDF.
- Train a Multinomial Naive Bayes classifier.
- Predict spam and ham messages.
- Evaluate the model using accuracy, precision, recall and F1 score.
- Test the classifier on new SMS messages.
- Save the trained model and TF-IDF vectorizer.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

---

## Project Workflow

```text
SMS Dataset
     |
     v
Data Exploration
     |
     v
Text Preprocessing
     |
     v
Train/Test Split
     |
     v
TF-IDF Vectorization
     |
     v
Multinomial Naive Bayes
     |
     v
Prediction
     |
     v
Model Evaluation
     |
     v
Spam / Ham Classification
