#  Sales Prediction Using Python

##  Project Overview

This project focuses on predicting product sales based on advertising expenditure across different media channels — **TV, Radio, and Newspaper**.

The project was completed as part of my **Data Science Internship** and demonstrates the complete machine learning workflow, starting from data exploration and visualization to model training, evaluation, and feature importance analysis.

---

##  Objective

The main objective of this project is to:

* Analyze advertising expenditure and sales data.
* Explore relationships between advertising channels and sales.
* Build a **Linear Regression** model as a baseline.
* Build a **Random Forest Regressor** for comparison.
* Evaluate model performance using **MAE, RMSE, and R² Score**.
* Identify which advertising channel has the highest impact on sales.

---

##  Dataset

The project uses the classic **Advertising dataset**, which contains advertising expenditure and corresponding sales values.

### Features

| Feature     | Description                          |
| ----------- | ------------------------------------ |
| `TV`        | Advertising expenditure on TV        |
| `Radio`     | Advertising expenditure on Radio     |
| `Newspaper` | Advertising expenditure on Newspaper |
| `Sales`     | Product sales — Target Variable      |

**Dataset Size:** 200 records

---

##  Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

##  Exploratory Data Analysis

The following EDA techniques were performed:

* Dataset shape and structure inspection
* Data type verification
* Missing value analysis
* Descriptive statistics
* Pairplot visualization
* Scatter plots
* Correlation matrix
* Heatmap visualization

### Visualizations

The project analyzes the relationship between:

*  TV Advertising vs Sales
*  Radio Advertising vs Sales
*  Newspaper Advertising vs Sales

The correlation analysis helps identify which advertising channels have stronger relationships with sales.

---

##  Machine Learning Models

### 1. Linear Regression

Linear Regression was used as the **baseline regression model**.

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

The model was trained using TV, Radio, and Newspaper advertising expenditure.

### 2. Random Forest Regressor

A **Random Forest Regressor** was also trained to compare its performance with the Linear Regression model.

Random Forest combines multiple decision trees and can capture non-linear relationships between features and the target variable.

---

##  Model Evaluation

The models were evaluated using:

### MAE — Mean Absolute Error

Measures the average absolute difference between actual and predicted sales.

**Lower MAE = Better performance**

### RMSE — Root Mean Squared Error

Measures prediction error while giving greater weight to larger errors.

**Lower RMSE = Better performance**

### R² Score

Measures how much of the variation in sales is explained by the model.

**Higher R² = Better performance**

---

##  Model Comparison

The trained models were compared using MAE, RMSE, and R² Score.

| Model             |   MAE |  RMSE |      R² Score |
| ----------------- | ----: | ----: | ------------: |
| Linear Regression | ~1.47 | ~1.79 |         ~0.90 |
| Random Forest     | ~0.67 | ~0.82 | Higher/Better |

Based on the evaluation, **Random Forest Regressor performed better in terms of prediction error** on the test data.

> Note: Exact values may vary depending on the train-test split and model parameters.

---

##  Feature Importance

Feature importance analysis was performed using the Random Forest model.

The analysis indicates that:

1. **TV** has the highest impact on sales.
2. **Radio** has the second-highest impact.
3. **Newspaper** has the lowest impact among the three channels.

This suggests that TV advertising is the most influential feature for predicting sales in this dataset.

---

##  Key Insights

* TV advertising has a strong positive relationship with sales.
* Radio advertising also contributes significantly to sales.
* Newspaper advertising has comparatively less influence.
* Random Forest produced lower prediction errors than the Linear Regression baseline.
* Machine learning can help businesses understand advertising effectiveness and support data-driven decisions.

---

##  Project Structure

```text
Sales-Prediction-Using-Python/
│
├── Advertising.csv
├── OASIS_task_5.ipynb
├── README.md
└── images/
    ├── pairplot.png
    ├── correlation_heatmap.png
    ├── tv_vs_sales.png
    ├── radio_vs_sales.png
    └── newspaper_vs_sales.png
```

---

##  How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Sales-Prediction-Using-Python.git
```

### 2. Navigate to the project folder

```bash
cd Sales-Prediction-Using-Python
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
OASIS_task_5.ipynb
```

and run the cells sequentially.

---

##  Future Improvements

Some possible improvements for this project are:

* Hyperparameter tuning of the Random Forest model.
* Cross-validation for more reliable model evaluation.
* Testing additional regression algorithms.
* Deploying the model using Flask or Streamlit.
* Creating an interactive sales prediction dashboard using Power BI or Tableau.

---

##  Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Exploratory Data Analysis
* Data visualization
* Correlation analysis
* Regression modeling
* Train-test splitting
* Model evaluation
* Feature importance
* Comparing machine learning models
* Using Scikit-learn for predictive analytics

---

##  Author

**Prajna Mondal**

B.Tech – Computer Science & Engineering

Aspiring **Data Analyst | Data Scientist**

###  Connect with Me

* LinkedIn: https://www.linkedin.com/in/prajna-mondal-1b864137a/ *

---

##  Acknowledgement

This project was completed as part of my **Data Science Internship** to gain hands-on experience with Python-based data analysis and machine learning.

If you find this project useful, feel free to the repository! Thank You
