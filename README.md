# 🏀 Basketball Game Winning Team Prediction
Python · Machine Learning · Sports Analytics

This project aims to predict the winning team in NCAA college basketball matchups using historical team performance data. By training supervised machine learning models, we identify patterns in statistical attributes to forecast game outcomes.

---

## 🎯 Objective

Build a machine learning model to predict whether a given basketball team will win or lose based on pre-game statistics and efficiency metrics.

---

## 📚 Dataset

The dataset is provided by IBM and can be downloaded from:

📥 [cbb.csv - NCAA College Basketball Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%206/cbb.csv)

It contains season-level statistics for NCAA Division I teams across multiple years. Each row represents a team’s performance for one season.

**Key Features:**

- `TEAM`, `CONF`: Team name and conference  
- `W`, `G`: Wins and games played  
- `ADJOE`, `ADJDE`: Adjusted offensive and defensive efficiency  
- `EFG_O`, `EFG_D`: Effective field goal percentages (offensive & defensive)  
- `ORB`, `DRB`: Offensive/defensive rebound rates  
- `TOR`, `TORD`: Turnover rates  
- `POSTSEASON`, `SEED`, `YEAR`: NCAA tournament outcomes and seedings

---

## ⚙️ Features

✅ Predicts which team is more likely to win  
📊 Uses advanced efficiency metrics (adjusted offense/defense, rebounding, turnovers, etc.)  
🤖 Implements multiple classifiers (Logistic Regression, Random Forest...)  
📉 Evaluates models using accuracy, confusion matrix, and other metrics  
📈 Data visualizations to explore relationships between stats and winning  

---

## 🧠 ML Workflow

1. **Data Cleaning & Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numeric features

2. **Feature Engineering**  
   - Compute relative stat differences between matchups  
   - Create binary labels for win/loss outcomes

3. **Model Training**  
   - Train supervised models: Logistic Regression, Random Forest, etc.  
   - Perform cross-validation

4. **Evaluation**  
   - Accuracy, precision, recall, F1-score  
   - Confusion matrix

5. **Insights & Interpretation**  
   - Feature importance  
   - Statistical trends in wins/losses

---
