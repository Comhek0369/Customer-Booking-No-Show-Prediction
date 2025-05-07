# Customer Booking No-Show Prediction

This repository contains a machine learning project that predicts whether a customer will show up for their booking, using structured customer data. The project includes exploratory data analysis (EDA), preprocessing, model training using a Random Forest classifier and evaluation.

## 📁 Files

- `customer_booking.csv`: The dataset containing customer booking information.
- `Python notebook 1.ipynb`: Exploratory Data Analysis (EDA) and data preprocessing notebook.
- `Train a RandomForest Model.ipynb`: Model training, evaluation and feature importance analysis.

## 📊 Dataset Overview

The dataset includes various customer attributes such as:
- Age
- Gender
- Booking details
- Other behavioral and demographic features

The target variable indicates whether a customer showed up for their booking.

## 🔍 EDA and Preprocessing

Key steps in preprocessing:
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Data visualization to understand feature distributions and correlations

## 🧠 Model Training

A **Random Forest Classifier** was used for predicting customer no-shows. The pipeline includes:
- Splitting the data into training and test sets
- Fitting the model on training data
- Evaluating performance with:
  - Accuracy
  - Classification report (precision, recall, F1-score)
  - Confusion matrix

## 📈 Results

- Good model performance on test data.
- Feature importance analysis to understand the drivers of customer behavior.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-booking-prediction.git
   ```
   
2. Navigate to the project folder and open the notebooks in Jupyter or VS Code.
   

3. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Future Improvements
Hyperparameter tuning

Try other classifiers (e.g., XGBoost, SVM)

Cross-validation and model selection

## Author: [ComHek]
## License: MIT
