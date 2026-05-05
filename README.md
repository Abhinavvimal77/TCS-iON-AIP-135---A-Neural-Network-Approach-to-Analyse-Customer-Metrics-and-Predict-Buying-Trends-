# Customer Buying Trends Prediction using Neural Networks

## Overview

This project focuses on analyzing customer data and predicting buying trends using a Neural Network model. The objective is to identify patterns in customer behavior and provide insights that can help businesses make data-driven decisions.

The model leverages demographic, behavioral, and transactional data to classify customers based on their purchasing tendencies.

---

## Problem Statement

Understanding customer purchasing behavior is essential for improving marketing strategies, customer retention, and revenue generation. This project aims to build a predictive model that can accurately classify customer buying trends based on historical data.

---

## Objectives

* Predict customer buying trends using machine learning techniques
* Analyze the impact of demographic and behavioral features on purchasing behavior
* Perform detailed exploratory data analysis (EDA)
* Build and evaluate a Neural Network model
* Generate actionable business insights

---

## Dataset Description

The dataset consists of customer-related attributes covering demographics, purchasing behavior, and satisfaction levels.

### Features

* `id` – Unique customer identifier
* `age` – Age of the customer
* `gender` – Customer gender
* `income` – Annual income
* `education` – Education level
* `region` – Geographic region
* `loyalty_status` – Loyalty program membership
* `purchase_frequency` – Frequency of purchases
* `purchase_amount` – Amount spent
* `product_category` – Preferred product category
* `promotion_usage` – Usage of promotions/discounts
* `satisfaction_score` – Customer satisfaction rating

---

## Methodology

### Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature scaling
* Target variable creation (customer spending/buying category)

### Exploratory Data Analysis (EDA)

* Distribution analysis of key variables
* Gender and income-based spending patterns
* Regional and product category insights
* Correlation analysis between numerical features
* Visualization of customer segmentation trends

### Model Building

* Neural Network implemented using Keras
* Dense layers with activation functions
* Hyperparameter tuning for optimization

### Model Evaluation

* Accuracy
* Precision
* Recall
* F1 Score

---

## Results

The Neural Network model achieved strong predictive performance:

* Accuracy: 85.94%
* F1 Score: 85.99%
* Precision: 86.02%
* Recall: 85.94%

The model effectively captures customer purchasing patterns and can be used for real-world business applications.

---

## Key Insights

* Higher income customers tend to spend more frequently
* Loyalty program members show stronger purchasing behavior
* Promotion usage significantly influences buying trends
* Satisfaction score correlates with repeat purchases
* Certain regions contribute more to overall revenue

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## Project Structure

```
├── data/
├── notebooks/
│   ├── Advanced_EDA.ipynb
│   ├── Neural_Network_Model.ipynb
├── images/
├── report/
├── README.md
```


---

## Future Scope

* Use advanced models like Random Forest, XGBoost, or Deep Learning architectures
* Deploy the model using Flask or Streamlit
* Integrate real-time customer data
* Improve feature engineering for better accuracy

---

## Conclusion

This project demonstrates the application of Neural Networks in predicting customer buying behavior. The insights generated can help businesses optimize marketing strategies, improve customer engagement, and enhance decision-making processes.

---

## Author

**Abhinav M**
TCS iON Internship Project
Vishwakarma University, Pune

---
