# 🌾 Agricultural Market Price Analysis & Prediction System

A Big Data Analytics and Machine Learning project that analyzes agricultural commodity prices and predicts market prices using Linear Regression and Decision Tree algorithms.

## 📌 Project Overview

The Agricultural Market Price Analysis & Prediction System is designed to analyze agricultural commodity prices collected from various APMC markets across India. The project uses machine learning techniques to identify relationships between price variables and predict the modal price of agricultural commodities.

The dataset was obtained from the Government of India's Open Data Platform (data.gov.in) and contains thousands of real-world market records.

---

## 🎯 Objectives

* Analyze agricultural market price data
* Study relationships between Minimum Price, Maximum Price, and Modal Price
* Build predictive machine learning models
* Evaluate model performance using statistical metrics
* Visualize agricultural market trends
* Support data-driven decision-making for farmers and traders

---

## 🛠 Technologies Used

* R Programming
* Big Data Analytics
* Machine Learning
* Linear Regression
* Decision Tree Regression
* Data Visualization
* Statistical Analysis

---

## 📊 Dataset Features

The dataset includes:

* State
* District
* Market
* Commodity
* Variety
* Grade
* Arrival Date
* Minimum Price (MinPrice)
* Maximum Price (MaxPrice)
* Modal Price (ModalPrice)

---

## 🤖 Machine Learning Models

### 1. Multiple Linear Regression

Used to predict Modal Price using:

* Minimum Price
* Maximum Price

Model Equation:

ModalPrice = β₀ + β₁(MinPrice) + β₂(MaxPrice)

### 2. Decision Tree Regression

Used to understand price patterns and generate prediction rules through tree-based learning.

---

## 📈 Data Analysis Process

1. Data Collection
2. Data Preprocessing
3. Data Cleaning
4. Train-Test-Validation Split
5. Model Training
6. Model Testing
7. Model Validation
8. Performance Evaluation
9. Data Visualization

---

## 📉 Performance Metrics

| Metric                                | Value  |
| ------------------------------------- | ------ |
| Multiple R²                           | 0.9999 |
| Adjusted R²                           | 0.9999 |
| RMSE (Linear Regression - Test)       | 28.76  |
| RMSE (Linear Regression - Validation) | 27.77  |
| RMSE (Decision Tree - Test)           | 811.32 |
| RMSE (Decision Tree - Validation)     | 835.89 |

### Key Finding

Linear Regression achieved excellent performance with 99.99% variance explained and very low prediction error, making it the most suitable model for this dataset.

---

## 📊 Visualizations

The project includes:

* MinPrice vs ModalPrice Scatter Plot
* MaxPrice vs ModalPrice Scatter Plot
* Decision Tree Visualization
* State-wise Data Distribution Analysis

---

## 🌟 Key Contributions

* Agricultural commodity price analysis using real-world government data
* Development of a predictive machine learning model
* Identification of strong relationships between price variables
* Data-driven insights for agricultural markets
* Visualization of pricing patterns and trends

---

## 🚀 Future Scope

* Multi-year agricultural price forecasting
* Real-time market price prediction
* Weather-based price analysis
* Mobile and Web Application Development
* Advanced Machine Learning Models
* Regional and Seasonal Trend Analysis

---

## 👩‍💻 Developer

**Mittika Jana**
B.Tech (Artificial Intelligence)
Amity University Kolkata (2024–2028)

**Interests:** Python • Machine Learning • Data Analytics • DBMS • Web Development

---

## 📜 License

This project is developed for academic and educational purposes.

