# Predictive-Model-for-Customer-Churn-in-Telecommunications
## Project Overview
This project develops a predictive model for a telecommunications company to identify customers at high risk of churning. By predicting when customers are likely to leave for a competitor, the company can take proactive measures to retain them. We utilize the Logistic Regression algorithm to analyze customer data and predict churn.

## Customer Churn with Logistic Regression
A telecommunications company is facing challenges with customers leaving their landline business for cable competitors. As analysts, our goal is to understand and predict which customers are likely to churn by analyzing various demographic and service usage data.

## About the Dataset
We will use a historical telecommunications dataset where each row represents one customer. The dataset includes:
- Customer churn in the last month
- Services each customer has signed up for
- Customer account information
- Demographic information about customers

## Installation
Clone this repository and install the required packages:
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt

## Data Acquisition
Download the dataset using the following command:

## Usage
Run the Python script to preprocess the data, train the model, and evaluate its performance:
python churn_model.py

## Data Pre-processing and Selection
Data pre-processing steps include selecting features, converting data types, and normalizing the dataset to prepare it for the Logistic Regression model.

## Model Building
We build our Logistic Regression model using Scikit-learn, configuring it with appropriate hyperparameters for regularization. We train the model with a training dataset and evaluate its performance on a test set.

## Performance Evaluation
The model's performance is evaluated using the following metrics:

##	Jaccard index
•	Confusion matrix
•	Precision, Recall, and F1-score
•	Log loss

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request.

## License
 See LICENSE for more information.

