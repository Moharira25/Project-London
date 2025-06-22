# CO3093 - Big Data and Predictive Analytics: London Airbnb Price Prediction

This repository contains the coursework submitted for the **CO3093 - Big Data and Predictive Analytics** module. The project aims to predict Airbnb listing prices in London using machine learning techniques.

---

## 📄 Overview

The project focuses on analyzing a dataset of London Airbnb listings to build predictive models for estimating the price per night of a property. The process includes:

- Data cleaning and preprocessing
- Exploratory data analysis
- Baseline and advanced modeling

For full details of the methodology, analysis, and evaluation, please see the report: **`Project_London_report.pdf`**.

---

## 📁 Files in this Repository

- `Project_London_report.pdf` — Detailed report covering all steps of the project  
- `Project_London_code.ipynb` — Jupyter Notebook with the complete code and analysis

---

## 🔍 Summary of Approach & Key Findings

- **Data Preparation:** Cleaned raw dataset by handling missing values, transforming variables, and removing outliers.
- **Exploratory Analysis:** Identified key price drivers such as `neighbourhood`, `accommodates`, and `property_type` using visual and statistical methods.
- **Modeling:**
  - Built a baseline **Linear Regression** model.
  - Used **K-Means Clustering** for market segmentation.
  - Developed a **Random Forest Regressor** for improved accuracy.
- **Results:** The final Random Forest model achieved a cross-validated **R² score of 0.79**, outperforming the baseline.

---

## ▶️ How to Run

### 🔧 Prerequisites

Make sure Python and the required libraries are installed. Install dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab
````

### 🚀 Launch Jupyter

Clone this repository and open JupyterLab:

```bash
jupyter lab
```

Then, open the file `Project_London_code.ipynb` to run the notebook.

---

## 🛠️ Tools and Libraries

* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`
* **Visualization:** `matplotlib`, `seaborn`
* **Statistical Analysis:** `scipy`
