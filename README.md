```markdown
# 🚀 CodeAlpha Data Science Internship Projects

This repository contains the completed data science and machine learning tasks submitted for the **CodeAlpha Data Science Internship**.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Repository Structure](#-repository-structure)
- [Task 1: Iris Flower Classification](#-task-1-iris-flower-classification)
- [Task 4: Sales Prediction using Python](#-task-4-sales-prediction-using-python)
- [Tech Stack](#-tech-stack)
- [Installation & Execution](#-installation--execution)
- [Author](#-author)

---

## 📖 Overview
- **Domain:** Data Science & Machine Learning
- **Tasks Completed:**
  1. **Task 1:** Iris Flower Classification (Multi-class Classification)
  2. **Task 4:** Sales Prediction using Python (Multiple Linear Regression)

---

## 📂 Repository Structure

```text
codealpha_tasks/
│
├── tasks.py             # Complete runnable script for both Task 1 and Task 4
├── requirements.txt     # Python dependencies
└── README.md            # Comprehensive project documentation

```

---

## 🌸 Task 1: Iris Flower Classification

### 1. Objective

Build a supervised machine learning model to accurately classify Iris flowers into three species (**Setosa**, **Versicolor**, and **Virginica**) using physical petal and sepal measurements.

### 2. Workflow

* **Data Ingestion:** Loaded the Iris dataset via `sklearn.datasets.load_iris`.
* **Exploratory Data Analysis (EDA):** Visualized feature distributions and inter-feature relationships.
* **Model Training:** Trained a **Random Forest Classifier** (`n_estimators=100`) on an 80:20 stratified train-test split.
* **Evaluation:** Evaluated performance using Confusion Matrix, Accuracy Score, and Classification Report.

### 3. Results

* **Model Accuracy:** `100%`
* **Precision / Recall / F1-Score:** `1.00` across all three flower classes.

---

## 📈 Task 4: Sales Prediction using Python

### 1. Objective

Analyze advertising expenditure across multiple media channels (**TV**, **Radio**, and **Newspaper**) and predict overall product sales volume using regression modeling.

### 2. Workflow

* **Dataset:** Advertising budget vs. sales dataset.
* **EDA & Correlation Analysis:** Evaluated Pearson correlation coefficients between advertising channels and sales output.
* **Model Building:** Trained a **Multiple Linear Regression** model on an 80:20 train-test split.
* **Evaluation Metrics:** Assessed model fit using $R^2$ Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

### 3. Key Findings & Performance

* **R² Score:** `0.90` (Explains ~90% of variance in sales volume)
* **Mean Absolute Error (MAE):** `~1.46`
* **Root Mean Squared Error (RMSE):** `~1.78`
* **Key Insight:** TV and Radio advertising budgets demonstrate the strongest positive correlation with product sales growth, while Newspaper spend shows minimal direct impact.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:**
* `pandas` - Data manipulation and analysis
* `numpy` - Numerical computing
* `scikit-learn` - Machine learning algorithms and evaluation metrics
* `matplotlib` & `seaborn` - Data visualization and plotting



---

## ⚙️ Installation & Execution

1. **Clone this repository:**
```bash
git clone [https://github.com/](https://github.com/)<your-username>/codealpha_tasks.git
cd codealpha_tasks

```


2. **Install required dependencies:**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

```


3. **Run the script:**
```bash
python tasks.py

```



---

## 👤 Author

* **Name:** Dhruv Prakash Mishra
* **Internship:** Data Science Intern at [CodeAlpha](https://www.google.com/search?q=https://codealpha.tech)

```

```
