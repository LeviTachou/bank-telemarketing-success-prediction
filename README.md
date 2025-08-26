# bank-telemarketing-success-prediction
A machine learning project that predicts the success of bank telemarketing campaigns by analyzing customer data. Performed EDA, feature engineering, and applied classification models (Logistic Regression, Decision Trees, Random Forest, Gradient Boosting), achieving ~80% accuracy.

# Bank Telemarketing Success Prediction  

## 📌 Project Overview  
This project aims to **predict the success of bank telemarketing campaigns** by analyzing customer data and applying machine learning techniques. The model helps banks identify clients who are more likely to subscribe to a term deposit, enabling smarter targeting and improving campaign efficiency.  

This project was completed as part of the **IIT Madras Data Science Program** and received a **Grade S** for performance.  

---

## 🎯 Objectives  
- Perform **Exploratory Data Analysis (EDA)** to understand customer behavior.  
- Identify key features influencing subscription intent.  
- Build **predictive models** using machine learning classifiers.  
- Evaluate model performance and provide actionable insights for business decision-making.  

---

## 🗂️ Dataset  
- The dataset contains details of bank telemarketing calls and customer demographics.  
- Features include: `age`, `job`, `marital`, `education`, `balance`, `contact`, `duration`, etc.  
- Target variable: `y` (whether the client subscribed to a term deposit).
-  
### Dataset Description
The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

Files
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
Input variables:
1 last contact date: last contact date
2 age (numeric)
3 job : type of job
4 marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
5 education (categorical: "unknown","secondary","primary","tertiary")
6 default: has credit in default? (binary: "yes","no")
7 balance: average yearly balance, in euros (numeric)
8 housing: has housing loan? (binary: "yes","no")
9 loan: has personal loan? (binary: "yes","no")
10 contact: contact communication type (categorical: "unknown","telephone","cellular")
11 duration: last contact duration, in seconds (numeric)
12 campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13 pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
14 previous: number of contacts performed before this campaign and for this client (numeric)
15 poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

Output variable (desired target):
16 target: has the client subscribed a term deposit? (binary: "yes","no")
---

## 🛠️ Tech Stack  
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 🔎 Methodology  
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling and transformation  

2. **Exploratory Data Analysis (EDA)**  
   - Statistical summaries  
   - Correlation heatmaps  
   - Visualizations of customer patterns  

3. **Model Development**  
   - Logistic Regression  
   - Decision Trees & Random Forest  
   - Gradient Boosting Classifiers  
   - Model evaluation using Accuracy, Precision, Recall, F1-Score  

4. **Results**  
   - Achieved accuracy of **~80%** with optimized models  
   - Derived key insights into customer behavior that improve targeting strategies  

---

## 📊 Results & Insights  
- Clients with longer call durations have higher chances of subscription.  
- Age, balance, and previous campaign outcomes strongly affect the prediction.  
- Decision Tree and Random Forest models performed better than Logistic Regression.  

---


