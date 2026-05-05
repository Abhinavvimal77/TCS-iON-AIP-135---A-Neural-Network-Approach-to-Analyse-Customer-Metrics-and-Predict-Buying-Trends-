🧠 TCS iON Industry Project
A Neural Network Approach to Analyse Customer Metrics and Predict Buying Trends
Institution: TCS iON | Project Type: Industry Project
Domain: Machine Learning | Retail Analytics | Customer Intelligence
Model Used: Multilayer Perceptron (MLP) Neural Network via Apache Spark (PySpark)

📌 Project Overview
In today's data-driven business landscape, companies rely on Artificial Intelligence and Machine Learning to decode customer behaviour, anticipate market trends, and drive smarter decisions. This project builds a Neural Network-based classification system that analyses customer demographic, profile, and transactional metrics to predict buying trends and spending behaviour — giving businesses a measurable competitive edge.

The model segments customers into Low, Medium, and High Spender categories, enabling targeted marketing, optimised inventory planning, and personalised customer experiences.

🎯 Project Objectives
#	Objective
1	Design and implement a Multilayer Perceptron (MLP) Neural Network to classify customer spending behaviour
2	Analyse the relationship between customer metrics (age, income, region, loyalty status, etc.) and buying patterns
3	Predict customer buying behaviour and market demand from large-scale sales and transaction datasets
4	Identify the optimal feature set that contributes most to prediction accuracy
5	Deploy the trained model and run inference on new, unseen customer data
🗂️ Dataset Description
Feature	Description	Type
age	Customer's age	Numerical
gender	Customer's gender (Male / Female)	Categorical
income	Annual income of the customer	Numerical
education	Highest education level attained	Categorical
region	Geographic region of the customer	Categorical
loyalty_status	Customer loyalty tier (Gold / Silver / Regular)	Categorical
purchase_frequency	How often the customer purchases (frequent / occasional / rare)	Categorical
product_category	Category of product purchased	Categorical
promotion_usage	Whether a promotion was used (1 = Yes, 0 = No)	Numerical
satisfaction_score	Customer satisfaction rating (1–10)	Numerical
purchase_amount	Total purchase amount (used to derive target variable)	Numerical
spending_level ⭐	Target Variable — Low / Medium / High Spender	Categorical
⭐ spending_level is derived from purchase_amount using the 25th and 75th percentile (IQR method):

High Spender → purchase_amount ≥ 75th percentile
Low Spender → purchase_amount ≤ 25th percentile
Medium Spender → everything in between
This model empowers businesses to:

🎯 Target High Spender profiles with premium marketing campaigns
📦 Optimise inventory based on predicted product category demand
🔁 Improve customer retention by identifying Low Spenders early
📍 Plan region-specific promotions based on spending patterns
💰 Reduce marketing spend wastage through precise customer segmentation
👩‍💻 Developed By : ABHINAV M
Field	Details
Project Title	A Neural Network Approach to Analyse Customer Metrics and Predict Buying Trends
Platform	TCS iON Industry Project
Environment	Jupyter Notebook + Apache Spark (Local)
Dataset Source	Kaggle — Customer Transaction Dataset
