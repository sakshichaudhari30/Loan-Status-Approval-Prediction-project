# 🏦 Loan Status Approval Prediction

## 📌 Project Overview

The **Loan Status Approval Prediction** project uses Machine Learning to predict whether a loan application is likely to be **approved or rejected** based on applicant and loan-related information.

The project focuses on data preprocessing, handling imbalanced data, exploratory data analysis, model building, evaluation, and deployment using **Streamlit**.

### 🚀 Live Deployment

🔗 **Try the Loan Approval Prediction App:**  
https://loan-status-approval-prediction-project-sakshi.streamlit.app/

---

## 🎯 Project Objective

The main objective of this project is to:

- Analyze loan applicant data.
- Identify important factors affecting loan approval.
- Handle missing values and categorical data.
- Handle the **imbalanced target variable**.
- Build and compare Machine Learning classification models.
- Evaluate model performance using appropriate classification metrics.
- Deploy the final model as an interactive web application.

---

## 🔄 Project Workflow

The project follows the complete Machine Learning workflow:

**Data Gathering → Data Understanding → Data Cleaning → EDA → Data Preprocessing → Train-Test Split → Handling Imbalanced Data → Model Building → Model Evaluation → Model Tuning → Model Saving → Deployment**

### 1. 📥 Data Gathering
- Collected the loan application dataset.
- Loaded the dataset using **Pandas**.

### 2. 🔍 Data Understanding
- Checked the number of rows and columns.
- Examined data types.
- Identified numerical and categorical features.
- Checked the target variable distribution.
- Used descriptive statistics to understand the dataset.

### 3. 🧹 Data Cleaning
- Checked for missing values.
- Handled missing values using suitable techniques.
- Checked and removed duplicate records where required.
- Corrected data types where necessary.
- Checked for inconsistent values.

### 4. 📊 Exploratory Data Analysis (EDA)
Performed EDA to understand patterns and relationships in the data using:

- Count plots
- Histograms
- Boxplots
- Correlation analysis
- Heatmap
- Distribution analysis

This helped identify important patterns and understand the relationship between applicant features and loan approval.

### 5. ⚙️ Data Preprocessing
Prepared the data for Machine Learning by:

- Separating features (`X`) and target (`y`).
- Encoding categorical variables.
- Scaling numerical features where required.
- Preparing the final feature set for model training.

### 6. ✂️ Train-Test Split
The dataset was divided into:

- **Training data** – used to train the model.
- **Testing data** – used to evaluate the model on unseen data.

### 7. ⚖️ Handling Imbalanced Data
The target variable was imbalanced, with significantly more records for one loan-status class.

To address this problem, **resampling/oversampling techniques** were used to improve the model's ability to identify the minority class.

### 8. 🤖 Model Building
Different classification algorithms were trained and compared.

The models were evaluated to determine which approach provided better prediction performance.

### 9. 📈 Model Evaluation
Model performance was evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

Since the dataset is imbalanced, **precision, recall, F1-score, and ROC-AUC** were considered along with accuracy.

### 10. 🎛️ Model Tuning
Hyperparameter tuning was performed where required to improve model performance and obtain a better-performing model.

### 11. 💾 Model Saving
The final trained model and required preprocessing components were saved using **Joblib** so they could be reused during deployment.

### 12. 🌐 Model Deployment
The trained Machine Learning model was integrated into a **Streamlit** web application.

Users can enter the required applicant details and receive a predicted loan approval status.

### 🚀 Live Application

**Loan Status Approval Prediction:**  
https://loan-status-approval-prediction-project-sakshi.streamlit.app/

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine Learning
- **Imbalanced-learn** – Handling imbalanced data
- **Joblib** – Model serialization
- **Streamlit** – Web application and deployment

---

## 📌 Key Learning Outcomes

- Understanding the complete Machine Learning classification workflow.
- Handling missing and categorical data.
- Performing Exploratory Data Analysis.
- Understanding and handling class imbalance.
- Comparing classification models using multiple evaluation metrics.
- Applying model tuning techniques.
- Saving and deploying a Machine Learning model using Streamlit.

---

## 🌐 Deployment

The final application is deployed using **Streamlit** and can be accessed here:

👉 **[Loan Status Approval Prediction App](https://loan-status-approval-prediction-project-sakshi.streamlit.app/)**

---

## 📁 Project Structure

```text
Loan-Status-Approval-Prediction/
│
├── dataset/
│   └── loan_data.csv
│
├── notebooks/
│   └── Loan_Status_Prediction.ipynb
│
├── model/
│   └── model.joblib
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 👩‍💻 Author

**Sakshi Chaudhari**

Aspiring Data Analyst | Python | SQL | Excel | Machine Learning
