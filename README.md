# Classifying Cybersecurity Incidents

## Overview

The project focuses on developing a machine learning model capable of categorizing and classifying cybersecurity incidents. By leveraging incident-specific attributes like type, severity, and attack vector, the project aims to automate the identification of cybersecurity threats, enabling organizations to detect and address vulnerabilities more effectively.

The project includes various stages such as data cleaning, exploratory data analysis (EDA), feature engineering, machine learning model development, and deployment of the classification system via a user-friendly **Streamlit** web application.

---

## Key Features

### 1. **Data Cleaning & Preprocessing**
- Manages missing values and outliers.
- Transforms and encodes data for improved model efficiency.

### 2. **Exploratory Data Analysis (EDA)**
- Examines features such as:
  - **Incident Type** (e.g., phishing, malware)
  - **Incident Severity** (e.g., low, medium, high)
  - **Attack Vector** (e.g., email, network breach)
  - **Source IP Address**, **Target System**, **Date, and Time**
- Identifies patterns and relationships between attributes.

### 3. **Model Development**
- Implements and trains machine learning models, including:
  - Random Forest
  - Logistic Regression
  - Decision Tree Classifier
  - XGBoost

### 4. **Model Evaluation**
- Assesses model performance using metrics such as:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**

---

## Technologies Used

- **Programming Language:** Python
- **Libraries & Tools:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Models:** Random Forest, Logistic Regression, Decision Tree Classifier, XGBoost
- **Data Visualization:** Matplotlib, Seaborn

---

## Data Overview

The dataset contains features that describe cybersecurity incidents, including:

- **Incident Type:** The type of event (e.g., phishing, malware, unauthorized access).
- **Incident Severity:** Severity levels such as low, medium, and high.
- **Attack Vector:** Methods used (e.g., email, network breach).
- **Source IP Address:** Origin of the attack.
- **Target System:** System or service affected (e.g., web server, database).
- **Date and Time:** Incident timestamp.

---

## Workflow

1. **Data Cleaning:**  
   - Handles missing values and removes irrelevant features.
   - Encodes categorical features and converts text into numerical representations.

2. **Feature Engineering:**  
   - Generates new attributes, such as extracting weekdays and hours from timestamps.
   - Encodes attack vectors into numeric formats.

3. **Model Training:**  
   - Trains multiple machine learning models to classify incidents based on features.

4. **Model Evaluation:**  
   - Compares models using metrics like accuracy, precision, recall, and F1-score.

---

## Model Performance

### **Model Comparison**

| Model                  | Accuracy | Macro-F1 Score | Precision | Recall |
|------------------------|----------|----------------|-----------|--------|
| **Logistic Regression** | 0.91     | 0.76           | 0.80      | 0.73   |
| **Decision Tree**       | 0.97     | 0.91           | 0.90      | 0.92   |
| **Random Forest**       | 0.99     | 0.98           | 0.98      | 0.98   |
| **XGBoost**             | 0.99     | 0.97           | 0.97      | 0.97   |

### **Best Model: Random Forest**
- Based on accuracy and Macro-F1 score, the **Random Forest** model outperforms others, achieving:
  - **Accuracy:** 0.99
  - **Macro-F1 Score:** 0.98
  - **Precision:** 0.98
  - **Recall:** 0.98

---

The project successfully demonstrates the potential of machine learning in automating cybersecurity threat classification, providing organizations with a powerful tool for proactive security management.