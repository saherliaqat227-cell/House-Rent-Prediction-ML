# 🏠 House Rent Prediction using Linear Regression

## 📊 Project Overview

This project focuses on predicting **house rent prices** using Machine Learning and **Linear Regression**.

The project includes data loading, data cleaning, exploratory data analysis, categorical data encoding, feature selection, model training, model evaluation, and visualization of house rent distribution.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📂 Dataset

The project uses the **House Rent Dataset**, which contains information related to rental properties.

Some of the features used for prediction include:

* BHK
* Size
* Floor
* Area Type
* Area Locality
* City
* Furnishing Status
* Tenant Preferred
* Bathroom
* Point of Contact

The target variable is:

* **Rent**

## 🔍 Project Workflow

The project follows these steps:

1. Load the dataset
2. Inspect the dataset using `head()`, `info()`, and `describe()`
3. Check and handle missing values
4. Perform Exploratory Data Analysis
5. Remove unnecessary columns
6. Encode categorical variables using Label Encoding
7. Select relevant features
8. Split the dataset into training and testing sets
9. Train a Linear Regression model
10. Make predictions
11. Evaluate model performance
12. Analyze Rent distribution using statistical measures and graphs

## 📈 Exploratory Data Analysis

Several visualizations were created to understand the dataset and the distribution of house rents.

### Visualizations Included

* Tenant Preferred Count Plot
* Correlation Heatmap
* House Rent Distribution Histogram
* Boxplot of House Rent
* Actual vs Predicted Rent Scatter Plot

## 📊 Statistical Analysis

The project analyzes the following measures for the **Rent** column:

* Mean
* Median
* Mode
* Minimum Rent
* Maximum Rent

The Rent distribution is **right-skewed**, with some extremely high rent values.

Because extreme values have a strong effect on the Mean, the **Median is a better measure of central tendency** for the Rent column.

## 🤖 Machine Learning Model

### Linear Regression

A Linear Regression model from Scikit-learn is used to predict house rent prices.

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

The model is trained using the selected property features and evaluated on the test data.

## 📏 Model Evaluation

The model is evaluated using:

* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**
* **R² Score**

The Linear Regression model achieved an:

**R² Score: 0.72**

Based on the project's evaluation criteria, the model performance is classified as:

**Moderate**

This means the model explains a reasonable amount of variation in house rent values, while there is still room for improvement.

## 📉 Actual vs Predicted Rent

An Actual vs Predicted graph is created to visually compare the actual house rent values with the values predicted by the Linear Regression model.

## 🎯 Project Objective

The main objective of this project is to understand the complete workflow of a Machine Learning regression problem, including:

* Data preprocessing
* Exploratory data analysis
* Feature encoding
* Feature selection
* Model training
* Model prediction
* Model evaluation
* Data visualization

## ▶️ How to Run

### 1. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 2. Open the Jupyter Notebook

```bash
jupyter notebook
```

### 3. Load the dataset

Make sure `House_Rent_Dataset.csv` is available and update the file path in the notebook if necessary.

### 4. Run the notebook cells sequentially

## 📁 Project Structure

```text
House-Rent-Prediction-ML/
│
├── House Rent Prediction.ipynb
└── README.md
```

👩‍💻 Author

Saher Liaqat

BS Information Technology Student
Minhaj University Lahore


