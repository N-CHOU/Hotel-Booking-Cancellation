Business Context
Hotel booking cancellations significantly impact profitability, resource utilization, and operational planning. Vacant rooms translate into lost revenue, wasted staff time, and poor forecasting accuracy. Traditional approaches such as overbooking or last-minute discounts often create reputational or financial risks. This project applies data analytics and machine learning to help hotels proactively identify high-risk bookings, design adaptive cancellation policies, and strengthen customer retention strategies.

Objectives:
1. Identify key factors that influence booking cancellations.
2. Predict the likelihood of a booking being cancelled using data-driven models.
3. Segment customers based on their cancellation risk and value contribution to support differentiated policies and pricing strategies.
4. Dataset and Methodology

A dataset from Kaggle was used, containing over 36 variables across booking, customer, financial, and behavioral categories. After data cleaning and feature selection, four analytical stages were implemented:
1. Exploratory Data Analysis – Assessed seasonality, lead-time effects, demographic patterns, and deposit type influence.
2. Predictive Modeling – Applied Logistic Regression (with PCA and L1/L2 regularization), CART, and Random Forest models to predict cancellations.
3. Model Evaluation – Compared model performance using accuracy, ROC-AUC, and k-fold cross-validation to ensure robustness.
   <img width="942" height="449" alt="image" src="https://github.com/user-attachments/assets/ac288a29-233e-42f0-ae2b-855c357b2dfe" />
4. Customer Clustering (K-Means) – Segmented guests based on cancellation risk and booking value to inform tailored marketing and policy design.
   <img width="937" height="515" alt="image" src="https://github.com/user-attachments/assets/1ccc6f59-9778-4495-b9d9-6429735c34d3" />


Key Findings:
1. Deposit type, lead time, and booking channel are the strongest predictors of cancellations.
2. Non-refundable deposits increase cancellation risk by over 16×, likely due to speculative or bulk agent bookings.
3. Long-lead bookings are far more prone to cancellation, while short-notice reservations are more stable.
4. Customers requiring parking, repeat guests, and direct bookings show the lowest cancellation risk.
5. Random Forest achieved the highest performance with 88% accuracy and ROC-AUC of 0.95, confirming its reliability for deployment.
6. Clustering revealed four distinct customer groups, enabling differentiated policies that balance flexibility for low-risk guests with stricter terms for high-risk segments.

Business Impact and Recommendations:
By integrating predictive modeling into reservation systems, hotels can:
1. Implement real-time cancellation-risk scoring to manage inventory proactively.
2. Offer dynamic deposit policies and flexible pricing tied to risk segments.
3. Optimize marketing campaigns to focus on high-value, low-risk customers.
4. Reduce cancellation-related revenue losses by an estimated 10–15%, improving occupancy forecasting and customer satisfaction.

Presentation:[Hotel Booking Cancellation_Presentation.pdf](https://github.com/user-attachments/files/23239557/Hotel.Booking.Cancellation_Presentation.pdf)
Dataset used: https://www.kaggle.com/datasets/muhammaddawood42/hotel-booking-cancelations/data

