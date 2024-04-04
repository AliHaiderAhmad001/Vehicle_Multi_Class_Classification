# Vehicle Type Classification

## Overview
This project aims to classify different types of vehicles, such as sedans, SUVs, and trucks, based on their features extracted from Craigslist ads. 

## Dataset
The dataset contains information on various vehicles listed on Craigslist, featuring 426880 examples and 26 attributes including vehicle type, manufacturer, model, year, condition, and more. The dataset was preprocessed to convert categorical features to binary features, bin odometer readings into bins, and handle missing and outlier values. The target variable 'type' was converted to numeric form for model training.

## Models Trained
Four different models were trained to classify vehicle types:
- Bernoulli Naive Bayes
- Logistic Regression
- Decision Tree
- XGBoost

Each model's performance was evaluated based on accuracy, precision, recall, and F1 score.

## Key Findings
- The Decision Tree and XGBoost models demonstrated the highest accuracy, precision, recall, and F1 scores, indicating their effectiveness in classifying vehicle types.
- Despite its computational complexity, XGBoost did not outperform the simpler Decision Tree model, highlighting the importance of model selection based on both performance and computational efficiency.

## Getting Started
### Prerequisites
- Python 3.x
- Libraries: NumPy, pandas, scikit-learn, xgboost


## License
This project is licensed under the MIT License - see the LICENSE file for details.
