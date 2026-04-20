# Experiment-14
DATA NORMALIZATION AND DATA CONVERSION

Experiment No.: 14

Name: Aanjneya Pankharaj
PRN: 25070123002
Batch: ENTC A1

Overview

This experiment focuses on two essential preprocessing techniques in data analysis: data normalization and data conversion. These methods are crucial for preparing raw data for machine learning models and analytical tasks.

The experiment is divided into two parts:

Part A: Data Normalization
Part B: Data Conversion
Tools and Technologies Used
Python
Pandas
NumPy
Scikit-learn
Objectives
To understand different normalization techniques
To scale numerical data effectively
To convert categorical data into numerical format
To prepare datasets for machine learning models
Part A: Data Normalization
Dataset Description

The dataset contains product-related information:

Product
Price
Units Sold
Discount
Techniques Implemented
1. Min-Max Normalization
Scales values between 0 and 1
Formula:
(X - Min) / (Max - Min)
Applied to Price, Units Sold, and Discount
2. Z-Score Normalization
Standardizes data based on mean and standard deviation
Formula:
(X - Mean) / Standard Deviation
Applied to Units Sold
3. Decimal Scaling
Scales data by dividing with powers of 10
Example: Price divided by 100000
4. Normalizing Multiple Columns
Applied normalization to multiple numerical columns simultaneously
Additional Dataset Operations

A real-world dataset (Amazon products) is used to apply normalization techniques:

Columns normalized: Price, Units Sold, Reviews
Methods used:
Min-Max Normalization
Z-Score based scaling
Decimal Scaling
Part B: Data Conversion
Dataset Description

The dataset includes customer order details:

Order ID
Customer Gender
Payment Method
Product Category
City
Order Value
Techniques Implemented
1. Label Encoding
Converts categorical values into numeric labels
Example: Male → 1, Female → 0
2. One-Hot Encoding
Converts categorical variables into binary columns
Prevents ordinal relationship assumptions
3. Encoding Multiple Columns
Applied encoding to multiple categorical features simultaneously
4. Dummy Encoding (Drop First)
Removes one column to avoid multicollinearity
Useful in regression models
Additional Dataset Operations

A student dataset is used for encoding:

Encoded Placement Status using Label Encoding
Applied One-Hot Encoding on Department
Performed multiple column encoding
Applied Dummy Encoding for efficient modelling
Key Insights
Normalization ensures uniform scale across features
Min-Max scaling is useful for bounded data
Z-score normalization is effective for statistical analysis
Encoding transforms categorical data into machine-readable form
One-hot encoding avoids misleading relationships in categorical data
Conclusion

This experiment demonstrates the importance of preprocessing techniques in data analysis. Proper normalization and conversion improve model performance and ensure accurate analysis. These techniques are essential steps in any data science workflow.

Future Scope
Application in machine learning pipelines
Feature scaling for deep learning models
Handling large-scale real-world datasets
Automated preprocessing using pipelines
