# 🤖 Machine Learning Projects by Nasih Rahman

This repository contains beginner-to-intermediate level machine learning projects implemented in Python. Each project is designed to reinforce key ML concepts and give hands-on experience with data preprocessing, modeling, evaluation, and deployment.

---

## 📁 Projects Included

### 1. 🚢 Titanic Survival Prediction
A logistic regression–based project to predict passenger survival on the Titanic dataset.

**Features:**
- Data cleaning and preprocessing (handling missing values, feature engineering)
- Exploratory Data Analysis (EDA)
- Feature encoding (`Sex`, `Embarked`, `Age group`, etc.)
- Model training using **Logistic Regression**
- Prediction and Kaggle submission file generation
- Countplot visualization of predicted survival outcomes

**Dataset:**
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- Files used: `train.csv`, `test.csv`

**Usage:**
1. Clone the repo or download the notebook.
2. Place `train.csv` and `test.csv` in the project folder.
3. Run the notebook step by step:
   - Data loading and inspection
   - Feature engineering and cleaning
   - Model training and evaluation
   - Submission file creation

**Main Libraries:**
- `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

**Output:**
- Model accuracy printed
- `submission.csv` generated for Kaggle

---

### 2. 📧 Naive Bayes Email Spam Classifier
Implements a Naive Bayes classifier **from scratch** to detect spam emails using word frequency analysis.

**Features:**
- Loads email data from `emails.csv`
- Text preprocessing (lowercasing, tokenization)
- Calculates word and class frequencies
- Implements Naive Bayes spam classifier (without using `scikit-learn`)
- Predicts the probability of an email being spam
- Allows manual predictions with your own text

**How it works:**
1. Loads and processes emails into tokens
2. Computes word frequencies for `spam` and `ham` classes
3. Applies Bayes' theorem to calculate posterior probabilities
4. Predicts spam likelihood and displays results

**Dataset:**
- `emails.csv` (text, label)

**Usage:**
1. Place `emails.csv` in the working directory.
2. Open and run the notebook.
3. Test predictions on your custom email samples.

**Main Libraries:**
- `pandas`, `numpy`

**Output:**
- Class and word frequencies printed
- Spam probability prediction for sample emails

---


