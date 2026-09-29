# Customer Segmentation

## Project Overview

This project uses **Machine Learning and K-Means Clustering** to segment customers based on their demographic and purchasing behavior. The analysis helps identify groups of customers with similar characteristics and provides insights that can support targeted marketing and customer engagement.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Streamlit
* Joblib
* Jupyter Notebook

## Key Steps

1. Loaded and explored the customer dataset.
2. Performed data cleaning and preprocessing.
3. Selected relevant customer features.
4. Standardized the features using `StandardScaler`.
5. Applied **K-Means Clustering** to create customer segments.
6. Used the Elbow Method to determine the number of clusters.
7. Visualized customer segments using PCA.
8. Saved the trained K-Means model and scaler using Joblib.
9. Developed a **Streamlit web application** to predict the customer segment for new customer data.

## Features

The segmentation is based on factors such as:

* Age
* Income
* Total Spending
* Web Purchases
* Store Purchases
* Web Visits
* Recency

## Result

The project successfully identifies different customer groups based on their behavior. The Streamlit application allows users to enter customer information and receive a predicted customer segment.

## Project Files

```text
customer_segmentation_thiranex/
│
├── Analysis_Model.ipynb
├── app.py
├── customer_segmentation.csv
├── kmeans_model.pkl
└── scaler.pkl
```
