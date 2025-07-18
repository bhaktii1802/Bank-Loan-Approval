
# Bank Loan Approval Prediction App 

## Project Overview:
The Bank Loan Approval Prediction App is a data-driven, machine learning-based web application designed to assist financial institutions in evaluating the creditworthiness of loan applicants. Built with Python and deployed using Streamlit, this project combines data preprocessing, feature engineering, and predictive modeling into a seamless user interface that mimics real-world loan approval workflows.

In the traditional loan processing pipeline, evaluating applications involves manually assessing various factors like the applicant's income, employment type, credit score, assets, and more. This approach is not only time-consuming but also prone to human bias and inconsistency. Our application addresses this by automating the decision-making process using a Logistic Regression model, trained on historical loan data, to instantly predict whether an applicant is likely to be approved or rejected for a loan.



![App Screenshot](https://raw.githubusercontent.com/bhaktii1802/Bank-Loan-Approval/main/dataset-cover.jpg)



## The model takes into account multiple user inputs including:

👨‍👩‍👧 Number of Dependents (0–5)

🎓 Education Status (Graduate / Not Graduate)

👔 Employment Type (Self-Employed / Not)

💰 Annual Income (₹0 to ₹10,000,000)

🏦 Requested Loan Amount (₹0 to ₹10,000,000)

🕒 Loan Duration (up to 20 years)

📊 CIBIL Score (0 to 800)

🏘️ Asset Value (Residential, Commercial, Luxury, and Bank-owned assets)

To optimize prediction performance:

- Data preprocessing involved removing irrelevant features like loan_id, encoding categorical data, and engineering a combined Assets feature.

- The model achieved ~82% accuracy on the test set and showed balanced precision/recall scores, indicating robust generalization on unseen data.

- A StandardScaler was applied to normalize financial features before model training.

The app allows users to input borrower details through a friendly UI and receive instant approval/rejection predictions. It mimics real-world conditions where creditworthiness is determined using combined financial indicators.

Whether you're a data scientist exploring deployment workflows or a fintech enthusiast looking to prototype loan screening solutions, this project offers a real-world use case demonstrating how machine learning can be integrated into interactive applications for impactful decision-making.

