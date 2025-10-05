![Project Banner](banner.png)
# 📘 README — Predictive ML Project (Module 7)

## 🔹 Project Overview
This project is part of **Module 7: Predictive Analytics**.  
The goal is to apply **Simple Linear Regression (SLR)** to real datasets, make predictions, visualize results, and practice communicating insights.  

We use two approaches:
1. **SciPy (stats.linregress)** — quick statistical regression.  
2. **scikit-learn (LinearRegression)** — ML workflow with train/test split.  

Finally, an **optional bonus** with the **California Housing dataset** is included to practice with larger data and multiple models.  

---

🔹 Repository Structure


    datafun-07-ml/
    │── data/                
    │   ├── ave_hi_nyc_jan_1895-2018.csv      # dataset 
    │  
    │── abdellah_boudlal_ml.ipynb # Main Jupyter notebook (Parts 1–5)
    │── requirements.txt # Project dependencies
    │── .gitignore # Ignore venv, cache, etc.
    │── banner.png
    │── Object_Oriented_Programming.ipynb
    │── README.md # Project documentation

## 🔹 Requirements
Python 3.10+ recommended.  
Install dependencies with:

pip install -r requirements.txt

Dependencies
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn

---

## 🔹 Notebook Parts

### Part 1 — Chart a Straight Line
- Plot Celsius vs Fahrenheit.  
- Review the line equation: y = mx + b.  
- Slope (m) = 9/5, Intercept (b) = 32.  

### Part 2 — Prediction with SciPy
- Load NYC January average high temperatures (1895–2018).  
- Clean the date column (truncate last 2 digits → keep only Year).  
- Use scipy.stats.linregress to calculate slope & intercept.  
- Predict 2024 and plot scatter + regression line.  

### Part 3 — Prediction with scikit-learn
- Use train_test_split to split dataset (train/test).  
- Train a LinearRegression model.  
- Evaluate with R² on train/test sets.  
- Predict 2024 and visualize regression line.  

### Part 4 — Insights
- Compare SciPy vs scikit-learn approaches.  
- Highlight differences between simple regression and ML workflow.  
- Reflect on model performance and predictions.  

### Part 5 — Bonus: California Housing
- Load dataset with fetch_california_housing.  
- Compare LinearRegression, Ridge, Lasso, DecisionTree.  
- Plot R² scores (train vs test).  
- Write insights: trade-offs, overfitting, generalization.  

---

## 🔹 How to Run

Clone this repository:

git clone https://github.com/aboudlal/datafun-07-ml.git
cd datafun-07-ml

Create and activate a virtual environment:

python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows PowerShell

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Then open abdellah_boudlal_ml.ipynb and run all cells.

---

## 🔹 Author
- Name: Abdellah Boudlal
- Course: Module 7 — Predictive ML Project
