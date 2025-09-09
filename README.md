# 🏅 Pentathlon: Next Product to Buy (NPTB) Modeling  

This project applies **predictive modeling and personalization analytics** to the **Pentathlon retail case study**. The challenge: determine which promotional email message (or no message at all) maximizes **customer purchases and profitability**, and use machine learning to deliver **personalized campaign recommendations**.  

---

## 📌 Project Overview  
Retailers often send promotional emails without knowing which type of message resonates best with each customer. Over-targeting leads to unsubscribes, while under-targeting wastes growth opportunities.  

The **Next Product to Buy (NPTB) framework** allows retailers to:  
- Predict which product or message a customer is most likely to respond to.  
- Optimize campaign allocation across multiple departments.  
- Balance **short-term sales** with **long-term customer retention**.  

**Objectives:**  
1. Predict customer response (purchase probability) after receiving different promotional messages.  
2. Estimate **expected profit per customer** considering both conversion likelihood and order size.  
3. Compare strategies: uniform messaging vs random assignment vs personalized recommendations.  
4. Propose a **new policy for promotional email allocation** based on machine learning insights.  

---

## 🔍 Methodology  

### 1. Data Preparation  
- **Data Structure:** 600,000 observations of customer–email pairs.  
- **Features:**  
  - Demographics: age, gender, income, education, children.  
  - Purchase history: frequency of purchases across 6 product departments.  
  - Experiment design: random assignment to one of six department emails or control (no email).  
- **Outcome Variables:**  
  - **Buyer:** Whether the customer made a purchase (yes/no).  
  - **Total Order Size (OS):** Value of purchase (conditional on buying).  

---

### 2. Modeling Approach  
- **Algorithms Used:**  
  - Logistic Regression  
  - Random Forests  
  - Neural Networks  
  - XGBoost  
- **Evaluation Metrics:** AUC, RMSE, R-squared, Gains Curves, Profit Analysis.  
- **Steps Followed:**  
  1. Predict purchase probability for each message per customer.  
  2. Predict expected profit (probability × order size × margin).  
  3. Identify the **optimal message** (or no message) for each customer.  
  4. Compare profit outcomes across different allocation strategies.  

---

### 3. Business Policy Simulation  
- **Uniform Messaging:** Same email sent to all customers.  
- **Random Assignment:** Current approach (status quo).  
- **Personalized Allocation:** Tailored message per customer, including “no message” option.  
- **Results:**  
  - Personalized targeting **significantly outperforms** both uniform and random approaches.  
  - Estimated lift in profitability for a campaign of **5M customers** when using personalization.  

---

## 🛠️ Tools & Libraries  
- **Python:** pandas, numpy, matplotlib, seaborn  
- **scikit-learn:** logistic regression, random forests, evaluation metrics  
- **XGBoost:** gradient boosting with hyperparameter tuning  
- **Neural Networks:** keras / tensorflow-based predictive modeling  
- **Visualization:** feature importance, gains curves, profit comparisons  
- **Jupyter Notebook:** reproducible workflow & documentation  

---

## 💡 Key Skills & Concepts  
- **Next Product to Buy (NPTB) Framework**  
- **Customer Personalization & Targeting**  
- **Machine Learning for Business**  
- **Feature Engineering & Model Tuning**  
- **Profit-Based Evaluation (beyond accuracy metrics)**  
- **Email Campaign Optimization**  
- **Data-Driven Marketing Strategy**  

---

## 🚀 Key Takeaways  
- **Sending fewer but smarter emails** boosts both customer satisfaction and profits.  
- **Personalized recommendations** outperform random or one-size-fits-all campaigns.  
- Machine learning helps uncover **which message works best for which customer segment**.  
- By including a **“no-message” option**, retailers can avoid over-targeting and churn.  

---
