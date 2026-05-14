This repository contains three machine learning and data science tasks ranging from exploratory data analysis and visualization to predictive modeling for business insights.

## Project Overview

### 1. Iris Dataset Visualization

**File:** `Iris_Vis.ipynb`
**Objective:** Perform exploratory data analysis (EDA) and visualize the structural characteristics of the famous Iris dataset.

* **Key Activities:**
* Data cleaning and handling missing values.
* Statistical summary of sepal and petal dimensions.
* **Visualizations:** * Scatter plots to analyze the relationship between Sepal Length and Sepal Width.
* Histograms to observe the distribution of physical features.
* Box plots to detect outliers and distribution spreads across features.





---

### 2. Bank Customer Churn Prediction

**File:** `Customer_churn.ipynb`
**Objective:** Predict whether a bank customer is likely to leave the bank (churn) based on their account information and demographics.

* **Model:** Random Forest Classifier.
* **Evaluation Metrics:** * **Accuracy:** $86.6\%$
* Confusion Matrix analysis to distinguish between True Positives and False Positives.


* **Feature Importance:** Identified that **Age**, **Estimated Salary**, and **Credit Score** are the primary drivers influencing a customer's decision to leave.
* **Preprocessing:** Utilized Label Encoding for binary features (Gender) and One-Hot Encoding for categorical features (Geography).

---

### 3. Personal Loan Acceptance Prediction

**File:** `Personal_loan.ipynb`
**Objective:** Build a classification model to predict if a customer will accept a personal loan offer based on a marketing campaign dataset.

* **Model:** Logistic Regression.
* **Evaluation Metrics:** * **Accuracy:** $\approx 89\%$
* **Business Insights:**
* Customers with positive outcomes in previous campaigns have a significantly higher likelihood of accepting new loan offers.
* Job types (specifically management and technicians) show higher response rates.
* Customers already holding housing loans are less likely to subscribe to a new personal loan.


* **Preprocessing:** Extensive use of Scikit-Learn's `LabelEncoder` to transform categorical demographic data into machine-readable formats.

---

## Installation & Requirements

To run these notebooks, you need Python 3.x installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```

## Usage

1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repo-name.git

```


2. Navigate to the directory:
```bash
cd your-repo-name

```


3. Open any notebook using Jupyter:
```bash
jupyter notebook Customer_churn.ipynb

```



## Author

Mubeen Hafeez Khan
