# Shopping Intent Prediction using K-Nearest Neighbors

This project implements a machine learning classifier to predict whether a user visiting an online shopping website will make a purchase during their session. Using session data such as page visits, duration, and user information, the classifier predicts purchase intent.

### Features

- Loads and preprocesses data from `shopping.csv`
- Converts categorical data into numeric format suitable for ML
- Uses a K-Nearest Neighbors (KNN) classifier with k=1
- Evaluates model performance with sensitivity (true positive rate) and specificity (true negative rate)
- Splits data into training and testing sets for validation

### Usage

Run the script as follows:

 `python shopping.py shopping.csv`

The script will output:

- Number of correct and incorrect predictions
- Sensitivity (true positive rate)
- Specificity (true negative rate)

### Dependencies

- Python 3.x
- scikit-learn

Install dependencies using pip:

`pip install scikit-learn`

