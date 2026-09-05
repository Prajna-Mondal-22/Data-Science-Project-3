#  Sales Prediction Using Python

##  Project Overview

This project focuses on predicting product sales based on advertising expenditure across three major media channels — **TV, Radio, and Newspaper**.

I developed this project to strengthen my practical understanding of **Data Analysis, Exploratory Data Analysis (EDA), Regression, Machine Learning, and Model Evaluation** using Python.

The project follows a complete machine learning workflow, starting from dataset exploration and visualization, followed by model training, evaluation, comparison, and feature importance analysis.

---

##  Objective

The main objectives of this project are:

* Analyze the relationship between advertising expenditure and sales.
* Perform Exploratory Data Analysis (EDA).
* Visualize relationships between advertising channels and sales.
* Build a **Linear Regression** model as a baseline.
* Build a **Random Forest Regressor** for comparison.
* Evaluate the models using **MAE, RMSE, and R² Score**.
* Identify which advertising channel has the greatest impact on sales.

---

##  Dataset

The project uses the **Advertising dataset**, containing advertising expenditure across different media channels and the corresponding sales.

### Dataset Features

| Feature     | Description                          |
| ----------- | ------------------------------------ |
| `TV`        | Advertising expenditure on TV        |
| `Radio`     | Advertising expenditure on Radio     |
| `Newspaper` | Advertising expenditure on Newspaper |
| `Sales`     | Product sales / Target variable      |

**Number of Records:** 200

---

##  Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and model evaluation
* **Jupyter Notebook** – Development environment

---

##  Exploratory Data Analysis

Before building the machine learning models, I performed Exploratory Data Analysis to understand the dataset and identify relationships between the variables.

The following analysis was performed:

* Dataset shape and structure inspection
* Data type checking
* Missing value analysis
* Descriptive statistics
* Pairplot of numerical features
* Individual scatter plots
* Correlation matrix
* Correlation heatmap

### Visual Analysis

I created individual visualizations for:

* **TV Advertising vs Sales**
* **Radio Advertising vs Sales**
* **Newspaper Advertising vs Sales**

The visualizations helped identify the relationship between advertising expenditure and sales.

---

##  Machine Learning Models

### 1. Linear Regression

I first implemented **Linear Regression** as the baseline model.

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

The model was trained using:

```text
TV
Radio
Newspaper
```

as input features, with:

```text
Sales
```

as the target variable.

---

### 2. Random Forest Regressor

I then implemented a **Random Forest Regressor** to compare its performance with the Linear Regression model.

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve predictive performance.

---

##  Model Evaluation

I evaluated both models using three commonly used regression metrics:

### MAE — Mean Absolute Error

Measures the average absolute difference between actual and predicted values.

**Lower MAE indicates better performance.**

### RMSE — Root Mean Squared Error

Measures the square root of the average squared prediction error and gives greater weight to larger errors.

**Lower RMSE indicates better performance.**

### R² Score

Measures how well the model explains the variation in the target variable.

**Higher R² indicates better performance.**

---

##  Model Comparison

The models were compared based on MAE, RMSE, and R² Score.

| Model                   |   MAE |  RMSE |      R² Score |
| ----------------------- | ----: | ----: | ------------: |
| Linear Regression       | ~1.47 | ~1.79 |         ~0.90 |
| Random Forest Regressor | ~0.67 | ~0.82 | Higher/Better |

Based on the evaluation results, the **Random Forest Regressor performed better in terms of prediction error** compared with the Linear Regression baseline.

> The exact results may vary depending on the train-test split and model configuration.

---

##  Feature Importance

Feature importance was analyzed using the Random Forest model to understand which advertising channel contributed most to sales prediction.

The analysis indicates that:

**TV → Highest importance**

**Radio → Second highest importance**

**Newspaper → Lowest importance**

Therefore, within this dataset, **TV advertising appears to be the most influential feature for predicting sales**.

---

##  Key Insights

From the analysis, I observed the following:

* TV advertising has a strong relationship with sales.
* Radio advertising also contributes significantly to sales.
* Newspaper advertising has comparatively less influence.
* Random Forest achieved lower prediction errors than the Linear Regression baseline.
* Advertising expenditure can be used to build predictive models for estimating sales.
* Feature importance provides useful insights into which advertising channels contribute most to the prediction.

---

##  Project Explanation Video

I also created a **step-by-step explanation video** for this project, where I explain the dataset, exploratory data analysis, visualizations, machine learning models, evaluation metrics, model comparison, and final insights.

The video is available on my **GitHub and LinkedIn** as part of my project portfolio.

###  Video

**LinkedIn:** [Add your LinkedIn video/post link here]


> The video demonstrates my understanding of the complete project workflow and explains how the machine learning models were implemented and evaluated.

---

##  Project Structure

```text
Sales-Prediction-Using-Python/
│
├── Advertising.csv
├── OASIS_task_5.ipynb
├── README.md
│
└── images/
    ├── pairplot.png
    ├── tv_vs_sales.png
    ├── radio_vs_sales.png
    ├── newspaper_vs_sales.png
    ├── correlation_heatmap.png
    └── residual_plot.png
```

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Sales-Prediction-Using-Python.git
```

### 2. Navigate to the project directory

```bash
cd Sales-Prediction-Using-Python
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```text
OASIS_task_5.ipynb
```

Run the cells sequentially to reproduce the analysis and model results.

---

##  Future Improvements

I plan to improve this project further by:

* Performing hyperparameter tuning.
* Applying cross-validation.
* Testing additional regression algorithms.
* Improving model optimization.
* Building an interactive sales prediction dashboard.
* Deploying the prediction model using **Streamlit or Flask**.
* Exploring more advanced machine learning techniques.

---

##  What I Learned

Through this project, I strengthened my practical knowledge of:

* Python for Data Science
* Pandas and NumPy
* Exploratory Data Analysis
* Data Visualization
* Correlation Analysis
* Train-Test Splitting
* Linear Regression
* Random Forest Regression
* Regression Evaluation Metrics
* Feature Importance
* Model Comparison
* Data-driven interpretation

---

##  About Me

I am a **Computer Science & Engineering graduate** with an interest in **Data Analytics, Data Science, Python, SQL, Machine Learning, and Business Intelligence**.

I enjoy working with data, extracting meaningful insights, and building practical machine learning solutions.

### Connect with me

 **LinkedIn:** [Add your LinkedIn profile]


---

##  Feedback

If you find this project useful or have suggestions for improvement, feel free to explore the repository and share your feedback.Thank you.

**Thank you for visiting my project!**
