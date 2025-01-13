# 🚀 Spaceship Titanic: Predicting Passenger Transport
This repository contains my solution for the **Spaceship Titanic** competition on [Kaggle](https://www.kaggle.com/competitions/spaceship-titanic). The goal is to predict whether passengers aboard the Spaceship Titanic were transported to an alternate dimension during a catastrophic event.

---

## 📂 Project Structure
```
├── data/                   
│   ├── train.csv           
│   ├── test.csv            
│   ├── sample_submission.csv 
├── notebooks/             
│   ├── spaceship_titanic.py
│   ├── submissions.csv     
├── requirements.txt
├── README.md
```

---

## 🔍 Problem Overview
The **Spaceship Titanic** competition is a binary classification challenge where the target is `Transported` (True/False), indicating whether a passenger was transported to another dimension.

### Dataset
- **Features**:
  - `HomePlanet`, `CryoSleep`, `Cabin`, `Destination`, `Age`, `VIP`, and various expenses like `RoomService` and `FoodCourt`.
- **Target**:
  - `Transported`: Binary label (True/False).

---

## 🚀 Approach
### 1. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of features and relationships with the target variable.
   - Identified and handled missing values.
### 2. **Feature Engineering**
   - Extracted new features from `Cabin` (e.g., deck, side).
   - Engineered aggregated features (e.g., total expenses).
   - Encoded categorical variables using one-hot encoding.
### 3. **Model Building**
   - Tried multiple machine learning models:
     - Logistic Regression
     - Random Forest
### 4. **Evaluation**
   - Assessed models using accuracy on the validation set.
   - Selected the best model for final predictions.

---

## 📊 Results
- Best Model: [Model Name]
- Validation Accuracy: **XX.XX%**
- Kaggle Submission Accuracy: **XX.XX%**

---
