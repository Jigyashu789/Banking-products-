# Banking-products-
# Marketing Campaign for Banking Products  
*Machine Learning Internship Project – Internship Studio*

## 📌 Project Overview
This project predicts which existing bank customers are most likely to accept a **personal loan** offer.  
By identifying high-probability borrowers, the bank can **increase conversions** and **reduce marketing costs**.

- **Dataset:** [Bank Loan Modelling (Kaggle)](https://www.kaggle.com/itsmesunil/bank-loan-modelling)  
- **Records:** 5,000 customers  
- **Goal:** Classify liability-based customers who are likely to purchase a personal loan.

---

## 🗂️ Data Description
Key attributes include:
- **Demographics:** Age, Experience, Income, Family, Education  
- **Banking Relationships:** Mortgage, Securities Account, CD Account, Online Banking, Credit Card usage  
- **Target:** `Personal Loan` (1 = accepted, 0 = declined)

---

## 🔑 Key Steps
1. **Data Cleaning & Preprocessing**  
   - Removed irrelevant columns (ID, ZIP)  
   - Handled negative/zero values, log-transformed skewed features  
   - One-hot encoded categorical variables, scaled numerical features.

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots, boxplots, and correlation heatmaps  
   - Identified key drivers such as Income, Credit Card spending, and Education.

3. **Model Building & Evaluation**  
   - Baseline: **Logistic Regression**  
   - Other Models: **Random Forest**, **XGBoost**, **SVM**, **KNN**  
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
   - Addressed class imbalance with class weighting.

4. **Hyperparameter Tuning**  
   - GridSearchCV to optimize Random Forest parameters.

5. **Business Insight**  
   - Ranked customers by predicted probability to guide targeted campaigns.  
   - Identified top predictive features influencing loan acceptance.

---

## 🛠️ Tech Stack & Skills
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost  
- **Machine Learning:** Classification, Feature Engineering, Model Evaluation, Imbalanced Data Handling  
- **Tools:** Jupyter Notebook, Git/GitHub  
- **Deployment Prep:** Model & scaler saved via `joblib`.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<Jigyashu789>/marketing-campaign-ml.git
   cd marketing-campaign-ml
