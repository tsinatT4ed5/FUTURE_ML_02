# 🏦 Bank Customer Churn Prediction — Machine Learning

A machine learning project focused on predicting **bank customer churn** and identifying customer characteristics associated with the likelihood of leaving a bank.

The project combines **exploratory data analysis, feature engineering, machine learning, model evaluation, feature importance analysis, and Power BI reporting** to demonstrate an end-to-end customer churn analytics workflow.

---

## 📌 Project Overview

Customer churn is an important challenge for financial institutions. Losing existing customers can affect revenue and increase the cost of acquiring new customers.

This project uses historical customer data to build machine learning models that estimate whether a customer is likely to leave the bank.

Beyond prediction, the project also explores **why customers may churn** by analyzing demographic, geographic, financial, and account-related characteristics.

The overall workflow was:

**Data → Cleaning → EDA → Feature Engineering → Model Training → Evaluation → Feature Importance → Power BI**

---

## 🎯 Objectives

The main objectives of this project were to:

* Analyze customer characteristics and churn patterns
* Identify factors associated with customer churn
* Prepare customer data for machine learning
* Build and compare multiple classification models
* Evaluate models using multiple performance metrics
* Identify the most influential features related to churn
* Export prediction results for visualization in Power BI
* Provide insights that could support customer retention strategies

---

## 📊 Dataset

The project uses the **Churn Modelling Dataset (`Churn_Modelling.csv`)**.

The dataset contains information related to:

* Customer demographics
* Geography
* Credit score
* Age
* Account balance
* Estimated salary
* Tenure
* Number of products
* Credit card status
* Active membership status
* Customer churn status (`Exited`)

The target variable is:

**`Exited`**

* `0` → Customer stayed
* `1` → Customer churned

---

## 🧹 Data Cleaning & Preprocessing

The dataset was prepared for analysis and modeling through several preprocessing steps.

### Data Cleaning

* Removed irrelevant identifier columns:

  * `RowNumber`
  * `Surname`
  * `CustomerId`
* Checked for missing values
* Handled numerical and categorical variables
* Prepared features for machine learning

### Feature Engineering

Relevant customer attributes were transformed and prepared to make them suitable for machine learning models.

Categorical variables were encoded appropriately, while numerical variables were prepared according to the requirements of the selected algorithms.

---

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand customer behavior and investigate relationships between customer characteristics and churn.

### Key Analysis Areas

* Distribution of **Age**
* Distribution of **Credit Score**
* Distribution of **Account Balance**
* Overall churn distribution
* Churn by **Gender**
* Churn by **Geography**
* Age vs. Churn
* Credit Score vs. Churn
* Balance vs. Churn
* Correlation analysis

### Visualizations

The project includes visualizations such as:

* Histograms and distribution plots
* Bar charts
* Box plots
* Correlation heatmaps
* Churn comparison charts

These analyses helped identify patterns that could be useful for the subsequent modeling stage.

---

## 🤖 Machine Learning Models

Three classification algorithms were implemented and compared:

### 1. Logistic Regression

Used as a baseline classification model and to establish a simple benchmark for churn prediction.

### 2. Random Forest

An ensemble learning algorithm used to capture nonlinear relationships between customer characteristics and churn.

### 3. XGBoost

A gradient boosting algorithm used to build a more powerful classification model and investigate whether boosting could improve predictive performance.

---

## 📏 Model Evaluation

The models were evaluated using multiple classification metrics:

| Metric        | Purpose                                                                   |
| ------------- | ------------------------------------------------------------------------- |
| **Accuracy**  | Overall proportion of correct predictions                                 |
| **Precision** | How many predicted churn cases were actually churn cases                  |
| **Recall**    | How many actual churn cases were correctly identified                     |
| **F1-score**  | Balance between precision and recall                                      |
| **ROC-AUC**   | Ability of the model to distinguish between churn and non-churn customers |

Using multiple metrics is important because a churn dataset can be imbalanced, meaning that accuracy alone may not provide a complete picture of model performance.

---

## 🔎 Feature Importance

Feature importance analysis was performed using the **Random Forest model** to identify the variables that contributed most strongly to its predictions.

The analysis helps answer questions such as:

* Which customer characteristics are most associated with churn?
* Are financial characteristics important?
* Does customer engagement affect churn?
* Which variables could be useful for customer retention strategies?

The **Top 10 features** were visualized to make the model's findings easier to interpret.

> **Important:** Feature importance indicates how useful a feature was to the model's predictions. It does not by itself establish a causal relationship between a feature and customer churn.

---

## 📊 Power BI Integration

The model's prediction outputs were exported for further analysis and visualization in **Power BI**.

This creates a connection between machine learning and business intelligence:

**Machine Learning → Predictions → Power BI → Business Insights**

Power BI can then be used to create interactive dashboards for exploring:

* Customer churn patterns
* Predicted churn
* Customer segments
* Important churn-related characteristics
* Retention opportunities

---

## 💡 Business Value

A churn prediction system can help financial institutions move from **reactive customer management to proactive retention**.

Potential applications include:

* 🎯 Identifying customers who may be at higher risk of leaving
* 📊 Understanding customer behavior patterns
* 💬 Supporting targeted customer retention campaigns
* 💰 Prioritizing retention efforts
* 📈 Monitoring churn trends through dashboards
* 🤝 Supporting data-driven customer relationship management

The model should be viewed as a **decision-support tool**, rather than an automatic replacement for business judgment.

---

## 🛠️ Technologies Used

### Programming & Data Analysis

* **Python**
* **Pandas**
* **NumPy**

### Machine Learning

* **Scikit-learn**
* **XGBoost**

### Data Visualization

* **Matplotlib**
* **Seaborn**

### Business Intelligence

* **Microsoft Power BI**

### Development

* **Jupyter Notebook**
* **Git & GitHub**

---


## 🚀 Future Improvements

Future versions of the project could include:

* Hyperparameter optimization
* Cross-validation for more robust model evaluation
* Advanced feature engineering
* Model explainability using SHAP
* Customer segmentation
* Churn probability scoring
* Integration with real-time customer data
* Automated Power BI dashboard refresh
* Development of a customer retention recommendation system

---

## 👩‍💻 Author

**Tsinat Demelash**

Data Science Graduate | Data Analytics | Machine Learning | Business Intelligence

🔗 **Portfolio:** https://tsinatt4ed5.github.io/my_portfolio/

🔗 **GitHub:** https://github.com/tsinatT4ed5

---

⭐ If you find this project useful or interesting, feel free to explore the repository and connect with me.
