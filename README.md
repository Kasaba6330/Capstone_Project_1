# Predicting Loan Success: A Data-Driven Analysis

!

## 📋 Project Overview

This project is a 2-week data-driven analysis aimed at predicting the success of loan applications. Using a dataset of borrower profiles, we identify the core factors that contribute to a successful loan (repayment) versus a failure (default).

In this analysis, the target variable has been mapped specifically such that:

* **1** = Success (Loan repaid/No default)
* **0** = Failure (Default)

## 🎯 Core Objectives

1. **Extract & Transform:** Process compressed raw data into a structured format for analysis.
2. **Identify Factors:** Determine which borrower attributes (Income, Credit Score, etc.) correlate with loan success.
3. **Predictive Modeling:** Build a Machine Learning model to predict the outcome of future loan applications.
4. **Insight Generation:** Visualize trends and feature importance to provide actionable financial insights.

---

## 🗺️ Project Roadmap

### **Task 1: Data Acquisition & Exploration**

* **Process 1.1: Environment Setup** – Configuring VS Code and extracting `Loan_default.csv` from the zip archive.
* **Process 1.2: Data Transformation** – Reversing the 'Default' logic to create a 'Success' column and saving the cleaned version as `Loan_success.csv`.
* **Process 1.3: Data Cleaning** – Handling missing values and verifying data types.
* **Process 1.4: Exploratory Data Analysis (EDA)** – Visualizing distributions and correlations.

### **Task 2: Modeling & Analysis**

* **Process 2.1: Feature Engineering** – Using One-Hot Encoding for categorical variables like `Education` and `EmploymentType`.
* **Process 2.2: Model Development** – Training a Random Forest Classifier to identify patterns in successful loans.
* **Process 2.3: Evaluation** – Assessing model performance using Accuracy, Precision, and Recall.
* **Process 2.4: Final Insights** – Extracting feature importance to rank the top drivers of loan success.

---

## 🛠️ Technology Stack

* **Environment:** VS Code
* **Language:** Python 3.x
* **Libraries:** * `Pandas`: Data manipulation and cleaning
* `Scikit-Learn`: Machine learning and preprocessing
* `Matplotlib` / `Seaborn`: Data visualization
* `Zipfile`: Compressed file handling


## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
