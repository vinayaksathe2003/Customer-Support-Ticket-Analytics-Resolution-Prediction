📊 Customer Support Ticket Analytics & Resolution Time Prediction
🔹 Project Overview
This project focuses on analyzing customer support ticket data to understand resolution patterns, SLA performance, and customer satisfaction trends.
The project also includes a machine learning model to predict whether a support ticket is likely to experience a long resolution time.
The objective is to help support teams improve operational efficiency and service quality using data-driven insights.

🧰 Tools & Technologies Used
Excel – Initial data cleaning and feature creation
Python – Core data processing and machine learning
Pandas & NumPy – Data manipulation and numerical analysis
Matplotlib & Seaborn – Data visualization
Scikit-learn – Machine learning modeling
Jupyter Notebook – Development environment

📂 Dataset Information
The dataset consists of 8,469+ customer support tickets with key attributes such as:
Ticket Priority
Ticket Channel
Ticket Type
Product Purchased
Ticket Subject & Description
First Response Time
Time to Resolution
Customer Satisfaction Rating

🧹 Data Cleaning & Feature Engineering
The following steps were performed to prepare the data:
Converted date and time columns into proper datetime format
Handled missing values in numerical and categorical columns
Removed invalid and negative resolution timestamps
Engineered new features:
Resolution_Hours
SLA_Breach
Long_Resolution_Flag
Description Length
Response Hour & Day

📊 Exploratory Data Analysis (EDA)
EDA was conducted to understand ticket patterns and service performance, including:
Ticket distribution by priority and channel
Ticket status analysis
Resolution time distribution
SLA compliance evaluation
Customer satisfaction vs resolution time
Priority vs resolution time comparison
These insights helped identify workflow inefficiencies and service gaps.

🤖 Machine Learning Model
🎯 Objective
To classify whether a support ticket will fall under Long Resolution or Normal Resolution.

✅ Models Used
Logistic Regression
Random Forest (Final Model)

📈 Final Model Performance
Model Used: Random Forest
Accuracy: 74%
Target Variable: Long Resolution Flag
Approach Used: TF-IDF, One-Hot Encoding, SMOTE for class balancing
The model is used as a decision-support tool for early identification of potentially delayed tickets.

📌 Key Business Insights
High volume of tickets comes from Phone and Social Media channels
Critical priority tickets take longer to resolve than expected
Most tickets meet SLA standards but satisfaction varies

Long-resolution cases are rare but impactful

Resolution time alone does not fully determine customer satisfaction
