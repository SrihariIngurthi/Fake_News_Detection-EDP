# Fake News Detection - EDP

This repository contains my weekly progress for the EDP Internship. The goal is to build a Fake News Detection system using Machine Learning.

## Week 1

- Created project structure
- Added required folders
- Installed required Python libraries
- Added Fake News datasets

---

## Week 2

### Topics Learned

- Data Loading with Pandas
- Exploratory Data Analysis (EDA)
- Data Preparation
- Feature and Label Creation
- Train-Test Split
- TF-IDF Vectorization
- Logistic Regression
- Model Evaluation

### Dataset

- Fake.csv
- True.csv

**Total Records:** 44,898

### Machine Learning Model

- Logistic Regression

### Results

- Accuracy: **98.27%**

## Week 3

### Topics Learned

- Text Preprocessing
- TF-IDF Vectorization
- Naive Bayes Classification
- Train-Test Split
- Model Evaluation

### Project

Built an SMS Spam Classifier using the SMS Spam Collection dataset.

### Dataset

- Total Messages: **5,572**
- Ham Messages: **4,825**
- Spam Messages: **747**

### Preprocessing

- Converted text to lowercase
- Removed punctuation and special characters
- Removed extra spaces
- Converted labels:
  - Ham → 0
  - Spam → 1

### Model

**Multinomial Naive Bayes**

### Results

| Metric | Score |
|---|---:|
| Accuracy | **96.32%** |
| Spam Precision | **1.00** |
| Spam Recall | **0.72** |
| Spam F1-Score | **0.84** |

### Files Added

- `Data/SMSSpamCollection`
- `Data/spam_dataset_processed.csv`
- `Models/spam_classifier.pkl`
- `Models/spam_tfidf_vectorizer.pkl`
- `notebooks/Week3_Spam_Classifier.ipynb`


### Folder Structure
```text
Data/
Models/
notebooks/
src/
README.md
Requirements.txt 

---
