# 🚀 CodeAlpha Data Science & Machine Learning Internship — Project Portfolio

This repository is a comprehensive collection of all tasks completed as part of the **CodeAlpha Data Science / Machine Learning Internship Program**. Each task covers a distinct real-world problem solved using Python and industry-standard ML/Data Science techniques.

---

## 📋 Table of Contents

1. [Task 1 – Iris Flower Classification](#task-1--iris-flower-classification)
2. [Task 2 – Unemployment Analysis](#task-2--unemployment-analysis)
3. [Task 3 – Car Price Prediction](#task-3--car-price-prediction)
4. [Task 4 – Sales Prediction](#task-4--sales-prediction)

---

## Task 1 – Iris Flower Classification

### 📌 Overview
A supervised Machine Learning model that classifies Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — based on their petal and sepal measurements.

### 🔍 What Was Done
- Loaded and preprocessed the Iris dataset
- Performed Exploratory Data Analysis (EDA) and feature visualization
- Split data into training and testing sets
- Trained a **Random Forest Classifier**
- Evaluated model performance and generated visualizations
- Saved the trained model as `iris_model.pkl`

### 📊 Visualizations
- Confusion Matrix
- Feature Importance Chart
- Pairplot
- EDA Graphs

### 📁 Folder Structure
```
Task1_IrisClassification/
│── images/
│── iris_classification.ipynb
│── iris_model.pkl
│── Iris.csv
│── requirements.txt
│── README.md
```


> 💡 The saved model (`iris_model.pkl`) can be integrated into a Flask or Streamlit web app.

---

## Task 2 – Unemployment Analysis

### 📌 Overview
A data analysis project that explores and visualizes **unemployment trends** over time using a flexible, auto-detecting pipeline that adapts to different CSV dataset formats.

### 🔍 What Was Done
- Automatically detected Date, Unemployment Rate, and Region columns from any uploaded CSV
- Cleaned missing values and standardized date formats
- Analyzed monthly and yearly unemployment trends
- Compared regional unemployment rates (where applicable)
- Generated comprehensive visualizations and automated insights

### 📊 Visualizations
- Line plots for overall unemployment trends
- Monthly and yearly average bar charts
- Boxplots for regional comparison
- Seasonal heatmap

### 🧠 Key Insights Generated
- Year with the highest and lowest unemployment
- Months with peak and lowest unemployment
- Regions most affected (when region data is available)

### ▶️ How to Run
1. Open the notebook in **Google Colab**
2. Upload your unemployment CSV file when prompted
3. Run all cells to generate analysis and visualizations

> 📂 Accepts any CSV with a Date column and Unemployment Rate column. Region column is optional.

---

## Task 3 – Car Price Prediction

### 📌 Overview
A Machine Learning regression model that predicts the **selling price of used cars** based on features like brand, age, mileage, fuel type, and transmission.

### 🔍 What Was Done
- Loaded and explored the car price dataset using Pandas
- Engineered a new `Car_Age` feature from the manufacturing year
- Encoded categorical variables (Fuel Type, Transmission, Selling Type, etc.)
- Trained a **Random Forest Regressor** for its robustness and accuracy
- Evaluated model using the R² score

### 📈 Results
| Metric | Value |
|--------|-------|
| R² Score | **0.9625** |
| Accuracy | **96.26%** |

### 📁 Dataset Features
| Feature | Description |
|---------|-------------|
| Year | Manufacturing year |
| Present Price | Current showroom price |
| Kms Driven | Total kilometres driven |
| Fuel Type | Petrol / Diesel / CNG |
| Selling Type | Dealer / Individual |
| Transmission | Manual / Automatic |
| Owner | Number of previous owners |
| **Selling Price** | *(Target variable)* |

### 📊 Visualizations
- Actual vs Predicted Price scatter plot (`actual_vs_predicted.png`)

---

## Task 4 – Sales Prediction

### 📌 Overview
A Machine Learning project focused on **predicting future sales** based on historical data, helping businesses make informed decisions about inventory, marketing, and revenue.

> 🔧 *This task is part of the CodeAlpha Internship Task 4. Full implementation details and results will be updated as the project progresses.*

---

## 🛠 Tech Stack

| Category | Tools & Libraries |
|----------|------------------|
| Language | Python |
| Data Manipulation | Pandas, NumPy |
| Machine Learning | Scikit-Learn |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook, Google Colab |
| Model Persistence | Pickle (`.pkl`) |

---

> 🎓 All tasks are completed as part of the **CodeAlpha Machine Learning / Data Science Internship Program**.
