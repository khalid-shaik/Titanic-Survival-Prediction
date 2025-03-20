# **🚢 Titanic Survival Prediction using Data Science & Machine Learning**
 
This project leverages Data Science techniques and Machine Learning models to predict passenger survival on the Titanic. The workflow encompasses data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation to derive insightful predictions and assess model performance.

## **📚 Project Overview**
Goal: Predict whether a passenger survived the Titanic disaster using historical data.

Algorithm Used: Logistic Regression (Classification Model)

Dataset: Kaggle Titanic Dataset

Objective: Identify patterns in passenger profiles that influenced survival.

## **🔎 Dataset Information**
The dataset contains two files:

train.csv - Used for training and validating the model.

test.csv - Used for making predictions and evaluating model performance.

## **🎯 Key Features:**
Pclass - Passenger class (1st, 2nd, 3rd)

Age - Age of the passenger

SibSp - Number of siblings/spouses aboard

Parch - Number of parents/children aboard

Fare - Passenger fare

Sex - Gender (encoded as male/female)

Embarked - Port of Embarkation (C, Q, S)

# **🧠 Data Science Workflow**
 **1. 📊 Data Preprocessing**
 
Handling Missing Values: Imputing missing Age with median and filling Embarked with the most frequent value.

Encoding Categorical Variables: Converting Sex and Embarked using one-hot encoding.

Feature Scaling: Normalizing Fare and Age for uniformity.

**2. 🔍 Exploratory Data Analysis (EDA)**

Survival Distribution: Analyzing survival rates across gender, class, and age groups.

Heatmaps and Pair Plots: Exploring feature correlations.

Outlier Detection: Identifying outliers in fare and age.

**3. ⚙️ Feature Engineering**

New Features: Creating new features like FamilySize and IsAlone to enhance model performance.

Feature Selection: Retaining only significant features using correlation analysis.

**4. 🤖 Model Building & Training**

Algorithm Used: Logistic Regression

Training the Model: Splitting the data into train-test sets and fitting the model.

Hyperparameter Tuning: Using GridSearchCV for optimal parameters.

**5. 📈 Model Evaluation**

Accuracy, Precision, Recall: Evaluating performance on test data.

Confusion Matrix: Visualizing classification results.

ROC-AUC Curve: Measuring model’s ability to distinguish between classes.

