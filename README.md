# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## 📌 Project Overview

This project is part of the **IBM Data Science Professional Certificate Capstone**. The objective is to predict whether the **SpaceX Falcon 9 first stage** will land successfully. Accurate prediction of landing success helps estimate launch costs and demonstrates how data science and machine learning can solve real-world aerospace problems.

The project covers the complete data science workflow, including data collection, data wrangling, SQL analysis, exploratory data analysis (EDA), interactive visualization, feature engineering, and machine learning.

---

## 🎯 Objectives

* Collect SpaceX launch data from APIs and web scraping.
* Clean and preprocess the collected data.
* Perform SQL queries to extract business insights.
* Conduct exploratory data analysis using Python and visualization libraries.
* Build interactive maps using Folium.
* Engineer features for machine learning.
* Train and evaluate multiple classification models.
* Identify the best-performing model for predicting Falcon 9 first-stage landing success.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Requests
* BeautifulSoup
* SQL (SQLite/Db2)
* Matplotlib
* Seaborn
* Folium
* Plotly Dash
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Structure

```
├── Data Collection with API
├── Web Scraping with BeautifulSoup
├── Data Wrangling
├── SQL Analysis
├── Exploratory Data Analysis (EDA)
├── Interactive Visual Analytics (Folium)
├── Feature Engineering
├── Machine Learning Models
├── dataset_part_1.csv
├── dataset_part_2.csv
├── dataset_part_3.csv
└── README.md
```

---

## 📊 Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

### Model Performance

| Model               |   Accuracy |
| ------------------- | ---------: |
| Logistic Regression |     83.33% |
| SVM                 |     83.33% |
| Decision Tree       | **94.44%** |
| KNN                 |     83.33% |

🏆 **Best Model:** Decision Tree
📈 **Accuracy:** **94.44%**

---

## 📈 Key Findings

* Launch sites are generally located near coastlines for safe rocket launches.
* Launch sites have convenient access to highways and railways for efficient logistics.
* Launch facilities are situated away from major cities to ensure public safety.
* Payload mass, launch site, orbit type, and booster reuse significantly influence landing success.

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/<your-username>/SpaceX-Falcon9-Landing-Prediction.git
```

2. Navigate to the project directory.

```bash
cd SpaceX-Falcon9-Landing-Prediction
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Run the notebooks sequentially.

---

## 📁 Dataset

The project uses SpaceX launch data obtained from:

* SpaceX REST API
* Wikipedia Launch Records
* IBM Skills Network datasets

---

## 📚 IBM Capstone Labs Included

* Data Collection with API
* Web Scraping
* Data Wrangling
* SQL Notebook
* Exploratory Data Analysis
* Interactive Visual Analytics with Folium
* Feature Engineering
* Machine Learning Prediction

---

## 📄 Results

The Decision Tree classifier achieved the highest accuracy of **94.44%**, making it the most effective model for predicting Falcon 9 first-stage landing success among the evaluated algorithms.

---

## 👤 Author

**Rohan Patnaik**

IBM Data Science Capstone Project

**Date:** 22 July 2026
