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

## 🗂️ Dataset Description
- The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.  
- Features include: `age`, `job`, `marital`, `education`, `balance`, `contact`, `duration`, etc.  
- Target variable: `y` (whether the client subscribed to a term deposit).
  
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


