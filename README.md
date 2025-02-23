
# Car Price Prediction with Machine Learning

This project demonstrates how to build a machine learning model to predict the selling price of a car based on various features such as its age, mileage, and fuel type. It uses Python and essential libraries for data analysis and machine learning.

---

## Project Overview

Car price prediction is a significant problem in machine learning, where multiple factors determine a car's value, including:

- Brand goodwill
- Horsepower and mileage
- Features (e.g., fuel type, transmission, etc.)
- Number of previous owners

This project aims to train and evaluate models to predict the selling price of a car based on these factors.

---

## Dataset

### Columns:

1. **Car\_Name**: Name of the car
2. **Year**: Year of manufacture
3. **Selling\_Price**: Selling price of the car (target variable)
4. **Present\_Price**: Current ex-showroom price
5. **Driven\_kms**: Distance driven in kilometers
6. **Fuel\_Type**: Type of fuel (Petrol/Diesel/CNG)
7. **Selling\_type**: Dealer or Individual sale
8. **Transmission**: Transmission type (Manual/Automatic)
9. **Owner**: Number of previous owners

---

## Project Workflow

### 1. **Data Preparation**

- Load the dataset using `pandas`.
- Engineer new features such as `Car_Age`.
- Perform one-hot encoding for categorical variables.

### 2. **Model Training**

- Split the dataset into training and testing sets.
- Train two machine learning models:
  - Linear Regression
  - Random Forest Regressor

### 3. **Model Evaluation**

- Evaluate models using metrics like Mean Squared Error (MSE) and R-squared (R²).

### 4. **Prediction**

- Predict the selling price of a car using the trained models.

---

## Installation

### Prerequisites

Ensure you have Python and Conda installed.

### Install Dependencies

Run the following command to install the required packages:

```bash
conda install pandas numpy scikit-learn
```

---

## Usage

### Running the Project

1. Clone the repository or download the project files.
2. Ensure the dataset file (e.g., `car data.csv`) is in the same directory as the code.
3. Open the Jupyter Notebook and execute the code cells step by step.

---

- Python Libraries: `pandas`, `numpy`, `scikit-learn`.

---
```

