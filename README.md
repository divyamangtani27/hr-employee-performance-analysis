# 📊 HR Employee Performance Analysis
### My First End-to-End Data Science Project

Complete data science project —built during my first year of B.Tech AIML at SIT, Pune, as part of the Data Preprocessing and EDA Lab (DPEL).
I went in knowing the basics of Python. I came out understanding how raw, messy data actually becomes something meaningful.


## 🧭 Why This Project

HR data is something everyone can relate to — employees, departments, performance, training. I wanted to work on a real dataset with actual noise and missing values, not a clean textbook example. This dataset had both, and that made it genuinely interesting to work through.


## 📁 Dataset

- **Source:** https://www.kaggle.com/datasets/sanjanchaudhari/employees-performance-for-hr-analytics
- **Size:** 17,417 employees×13 features
- **Includes:** department, education, gender,age, trainings taken, KPIs met, awards won, avg training score,prior rating, etc 


## 💡 What I Actually Learned Building This

Things the lectures don't always teach:

Data Loading — reading a real CSV and understanding what you're looking at before touching anything
Data Understanding — checking shape, dtypes, missing values, duplicates, and basic statistics before assuming the data is clean
Handling NA Values — filling nulls with median for numerical columns, mode for categorical ones, and understanding why each choice matters
Label Encoding — converting categories like gender and recruitment channel into numbers a model can use
One-Hot Encoding — handling multi-class columns like department and education without creating a false ordinal relationship
Visualisations — histograms, scatter plots, boxplots, correlation heatmaps, KDE plots, pairplots, Z-score outlier detection; making data visible changed how I understand it
Z-Score — using it not just as a formula but as an actual tool to spot outliers in each feature
Random Forest Regressor — training my first proper ML model, splitting data, and evaluating it with real metrics


## 🗂️ What does the  Analysis Covers

| Section | What I did |
|---|---|
| A) Data Understanding | shape, dtypes, missing values, duplicates, basic stats |
| B) Data Preprocessing | null handling, gender cleaning, column renaming, fixing types |
| C) Feature Transformation | Label Encoding, One-Hot Encoding, StandardScaler |
| D) EDA & Visualisations | histograms, scatter plots, boxplots, correlation heatmap, outlier plots |
| E) Multivariate Analysis | pairplot, KDE plots, Spearman heatmap, covariance matrix |
| F) Prediction Model | Random Forest Regressor with MSE, MAE, RMSE, R² evaluation |


## 🔍 Key Findings

- Employees who met KPIs (>80%) consistently had higher average training scores
- Technology and Analytics departments showed higher median training scores
- KPIs met and prior rating had the strongest correlation among all features
- Average training score stayed fairly consistent across all age groups — age alone doesn't predict performance
- Sales & Marketing had the highest employee headcount; Bachelor's degree was the most common education level


## 🤖 Model Results

| Metric | Value |
|---|---|
| Model | Random Forest Regressor |
| MSE | 1.4607 |
| MAE | 0.9462 |
| RMSE | 1.2086 |
| R² Score | 0.036 |

--> The R² is low because `prior_rating` (a 1–5 scale) doesn't have much variance to predict — the real value of this project is in the EDA and the patterns found through visualisation.


## 🛠️ Tools Used


Python · pandas · numpy · seaborn · matplotlib · scikit-learn


## 🚀 How to Run It

1. Download the dataset from the Kaggle link above
2. Open the `.ipynb` in Google Colab
3. Run the first cell → click Choose File → upload the CSV
4. Runtime → Run All and you're good to go

### This is just the beginning — I would love to work on many more projects and there is a lot more ahead to learn and build.


# 👩‍💻 About Me

Divya Mangtani · B.Tech AIML · Symbiosis Institute of Technology, Pune · Batch 2025–29

First-year AIML student who enjoys finding patterns in data and building things from scratch in Python. Currently focused on Data Science and ML, with growing interest in Computer Vision and Fintech AI. Not just learning for exams — learning to build things that matter.

This is just the beginning — there is a lot more ahead to learn and build. ✨


