# Exam Project - Python Solutions

This repository contains solutions to two exam tasks.  
Each task has its own Python program and instructions on how to run it.  

---

## 📌 Task 1: Spam Detection with Logistic Regression

**File:** `spam_detection.py`  

This program trains a Logistic Regression model to classify emails as **spam** or **legitimate**.  
It uses a dataset (`m_takashvili2024_356718.csv`) with the following features:  
- `words`: Number of words in the email  
- `links`: Number of links in the email  
- `capital_words`: Number of capitalized words  
- `spam_word_count`: Number of spam-related keywords  
- `is_spam`: Target label (1 = Spam, 0 = Legitimate)  

### 🔧 How to run Task 1

1. **Prepare the dataset**  
   Make sure the dataset file `m_takashvili2024_356718.csv` is in the same folder as `spam_detection.py`.  
   This dataset contains labeled email examples with features needed for training the model.

2. **Install required libraries**  
   Before running the script, install the necessary Python libraries if not already installed:
   ```bash
   pip install pandas scikit-learn matplotlib joblib
