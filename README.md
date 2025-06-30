Final Project – Data Science Course (Internshala)
# Term-deposit-prediction-model

This project aims to predict whether a client will subscribe to a term deposit based on their demographic data and telemarketing call details. The goal is to assist a retail bank in identifying potential customers most likely to convert, helping reduce telemarketing costs and improve campaign efficiency.

## 🧩 Problem Statement

A retail banking client wants to optimize their **telephonic marketing campaigns** used to sell **term deposits**—a key revenue source.

> Telephonic campaigns are costly and time-consuming. The bank wants to **predict in advance** which clients are likely to subscribe to the term deposit so it can **target only those clients**, saving resources.


## 📁 Dataset Information

You are provided with:

- `train.csv` – used to train the classification model.
- `test.csv` – used for generating predictions.

### 📚 Features (Selected)

| Variable | Description |
|----------|-------------|
| ID | Unique client ID |
| age | Age of the client |
| job | Job type |
| marital | Marital status |
| education | Education level |
| default | Has credit in default? |
| housing | Has a housing loan? |
| loan | Has a personal loan? |
| contact | Contact communication type |
| month | Contact month |
| day_of_week | Day of week of contact |
| duration | Duration of the call |
| campaign | Number of contacts in current campaign |
| pdays | Days since last contact |
| previous | Number of contacts before this campaign |
| poutcome | Outcome of the previous campaign |
| subscribed (target) | Whether the client subscribed to a term deposit |

## 🧠 Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis
   - Feature correlation

3. **Model Building**
   - Logistic Regression
   - Decision Trees / Random Forest / XGBoost (optional)
   - Accuracy evaluation on test set

4. **Evaluation**
   - Metric: **Accuracy**
   - Used `solution_checker.xlsx` for score validation


## 📊 Results

- Best Model: _To be updated_ (e.g., Logistic Regression)
- Accuracy Score: _To be updated from your solution_checker.xlsx result_

