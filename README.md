# Shipment Pricing Prediction

## 📦 Project Overview
The **Shipment Pricing Prediction** project aims to predict shipment prices based on various factors in the supply chain domain using machine learning techniques. This project addresses the growing need for accurate predictions in the rapidly evolving supply chain analytics market.

## 🚀 Technologies Used
- **Machine Learning**: Various regression models
- **Python**: Programming language for data analysis and modeling
- **Libraries**: 
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Flask

## 🔍 Problem Statement
The supply chain analytics market is projected to grow significantly, with organizations needing to optimize pricing strategies. This project focuses on predicting shipment pricing using available data to help supply chain leaders make informed decisions.

## 🔄 Architecture & Process Flow
### Process Flow
![Screenshot 2024-10-21 192106](https://github.com/user-attachments/assets/4769bfdb-4777-4845-833b-b0405f3447eb)
 <!-- Ensure to replace with the correct path to your image -->

### Data Validation and Transformation
- **Missing Values**: All missing values were replaced with the mode (most frequent value).
- **Numerical Columns**: Standardized to prevent data leakage using pipelines.
- **Categorical Columns**: Encoded using either label encoding or one-hot encoding.

### Model Training
![Screenshot 2024-10-21 192043](https://github.com/user-attachments/assets/b38f85b8-5d8c-4688-b1ef-20f8042852a3)
  
- Accumulated data was exported to Python and read using Pandas.
- Performed exploratory data analysis (EDA) to identify distributions, outliers, and trends.
- Checked for null values; if present, they were imputed.
- Encoded categorical values into numeric values and scaled numerical features using StandardScaler.
- New features were created to enhance model building based on business insights.

### Prediction
- Optimized the model for accuracy with a training R-squared of 0.998273 and a test R-squared of 0.991598.
- Key features: `Days to Process`, `Line Item Insurance`, `Shipment Mode`, `Freight Cost`.

### Project Output Result
![Project Output Result] ![Screenshot 2024-10-21 192322](https://github.com/user-attachments/assets/5eef75a0-e9b0-4001-b154-20d5e9dddf64)

- Training R²: 0.998273
- Test R²: 0.991598
- Important features identified: `Days to Process`, `Line Item Insurance`, `Shipment Mode`, `Freight Cost`.

## 📊 Dataset
- **Dataset Link**: [Click here!](https://www.kaggle.com/datasets/divyeshardeshana/supply-chain-shipment-pricing-data)

## 🛠️ Installation
To run this project, you will need Python and the required libraries. Set up a virtual environment and install dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn flask
