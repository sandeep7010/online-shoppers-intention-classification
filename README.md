
---

# Online Shoppers Intention Prediction

## Overview

This project uses **data science and machine learning techniques** to predict whether a visitor to an e-commerce website will generate revenue (make a purchase) or not. The dataset contains information about user behavior during online sessions, including page visits, browsing duration, traffic source, and visitor type.

The goal of this project is to analyze customer browsing patterns and build predictive models that help businesses **understand purchase behavior and improve conversion rates**.

---

# Project Workflow

### 1. Data Collection

* Dataset: **Online Shoppers Purchasing Intention Dataset**
* Contains **12,330 user sessions** with **18 features**
* Includes behavioral, temporal, and visitor information.

### 2. Data Understanding

* Examined dataset structure and feature types.
* Identified numerical and categorical variables.
* Checked class distribution of the **Revenue** target variable.

### 3. Data Preprocessing

* Handled missing values if present.
* Converted categorical features such as **Month, VisitorType, Weekend**.
* Encoded categorical variables using **Label Encoding / One-Hot Encoding**.
* Feature scaling applied where required.

### 4. Exploratory Data Analysis (EDA)

* Analyzed user behavior patterns.
* Examined relationships between features and revenue generation.
* Visualized patterns using plots and correlation analysis.

### 5. Feature Engineering

* Selected important behavioral metrics such as:

  * Page duration
  * Bounce rate
  * Exit rate
  * Page value
* Transformed categorical features for model compatibility.

### 6. Model Building

Trained multiple machine learning models including:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors
* Support Vector Machine

### 7. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

The best performing model was selected based on overall performance and generalization.

---

# Key Insights

* **ProductRelated pages and duration** strongly influence purchase decisions.
* **PageValues** has a high correlation with revenue generation.
* High **bounce rate and exit rate** usually indicate lower purchase probability.
* **Returning visitors** are more likely to make purchases than new visitors.
* Traffic sources and seasonal factors such as **month and special days** can impact buying behavior.

These insights help businesses improve **customer targeting, website design, and marketing strategies**.

---

### Tech Stack 

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**
