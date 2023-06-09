
# Loan Prediction Model

This project aims to develop a machine learning model to predict the risk level of loans based on certain features. The model uses logistic regression and incorporates data resampling techniques to handle imbalanced data.

## Description

The loan prediction model uses a logistic regression algorithm to predict whether a loan is healthy (0) or high-risk (1). The project includes data preprocessing, model training, and evaluation steps. It also demonstrates how to address class imbalance using oversampling techniques.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Results and Evaluation](#results-and-evaluation)
- [Conclusion](#conclusion)

## Installation

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Download the loan dataset from [source](insert_link) and place it in the `Resources` directory.
4. Run the main script or execute the provided Jupyter Notebook to reproduce the results.

## Usage

To use the loan prediction model:

### Step 1: Data Preparation

- Preprocess the loan dataset by handling missing values, encoding categorical variables, and performing feature scaling.

### Step 2: Model Training

- Train the logistic regression model on the preprocessed data.
- Implement oversampling using the RandomOverSampler from the imbalanced-learn library.
- Fit the oversampled data to the logistic regression model.

### Results and Evaluation

The model's performance can be evaluated using the following metrics:

#### Accuracy Score

- The accuracy score indicates the overall accuracy of the model's predictions.

#### Confusion Matrix

- The confusion matrix provides insights into the model's performance for each class (healthy loan and high-risk loan).

#### Classification Report

- The classification report displays precision, recall, and F1-score for each class, allowing an in-depth evaluation of the model's performance.

### Conclusion

The logistic regression model, trained on oversampled data, demonstrates promising results in predicting loan risk levels. By addressing class imbalance, the model achieves improved performance on high-risk loan predictions.



## License

This project is licensed under the [MIT License]

## Contact

For any questions or inquiries, please contact [Kacie Motley](kaciemotley1515@gmail.com)
