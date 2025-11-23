# Differentially Private Analysis of U.S. Household Income Statistics

This repository contains the complete implementation of a Differential Privacy (DP) pipeline applied to U.S. Household Income statistics.  
The project includes data preprocessing, exploratory data analysis (EDA), baseline and DP statistical queries, Laplace and Gaussian mechanisms,  
privacy–utility analysis, machine learning with baseline and DP-SGD models, visualizations, and final analytical summaries.

---

---

## 🚀 How to Run This Project

### **1. Install dependencies**
Use the provided requirements file:

```bash
pip install -r requirements.txt
````

### **2. Launch the Notebook**

```bash
jupyter notebook notebooks/dp_income_analysis.ipynb
```

### **3. Run All**

The notebook will execute the entire pipeline:
```bash
✔ Load & clean dataset
✔ Perform EDA
✔ Compute baseline statistics
✔ Apply DP mechanisms (Laplace, Gaussian)
✔ Generate DP-perturbed statistics
✔ Train baseline & DP-SGD ML models
✔ Produce all plots & metrics
✔ Save outputs to `data/processed` and `results` folders
```
---

## 📊 Outputs Generated

### **Differential Privacy Outputs**

* DP Mean, Median, Stdev for each ε
* Laplace vs Gaussian comparisons
* Privacy–utility trade-off curves
* DP evaluation metrics (MAE, RMSE, Bias, Relative Error)

### **Machine Learning Outputs**

* Baseline Linear Regression model
* DP-SGD privacy-preserving regression model
* Prediction accuracy comparisons
* Error distribution plots

---

## 🧠 Key Concepts Demonstrated

* Differential Privacy
* Global Sensitivity
* Laplace Mechanism
* Gaussian Mechanism
* DP-SGD Optimization
* Regression Modeling
* Privacy vs Utility Trade-Off
* Statistical and ML Evaluation

---

## 📄 Dataset Source

Kaggle Dataset:
**U.S. Household Income Statistics with Geo-Locations:**
[US Income Stat w Geo Location by Goldenoakresearch](https://www.kaggle.com/datasets/goldenoakresearch/us-household-income-stats-geo-locations)

Place the dataset in:

```
data/raw/us_income_raw.csv
```

---

## 👨‍💻 Contributors

* **Muttaki I. Bismoy**

---

## 📜 License

MIT License (modify as needed)

---

