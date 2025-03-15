**Student Performance Prediction**

This repository contains the implementation and analysis of predicting student performance using a dataset that examines various influencing factors. The implementation includes two parts:

Linear Regression from scratch using only numpy and pandas.

Regression using Python libraries such as scikit-learn.

The project is divided into specific tasks as outlined below:

Dataset

The dataset used is the Student Performance Dataset, available here. The dataset examines factors such as hours of study, previous scores, extracurricular activities, and more.

Implementation Details

Task 1: Linear Regression from Scratch

1. Identify Dependent and Independent Variables (2 marks)

Dependent Variable: Student’s performance.

Independent Variables: Hours of study, previous score, extracurricular activities, duration of sleep, sample question papers practiced.

2. Exploratory Data Analysis (EDA) (8 marks)

Data preprocessing:

Handling missing values.

Encoding categorical variables (e.g., Extracurricular Activities).

Normalizing numerical variables.

Visualization:

Correlation heatmap.

Pair plots of features vs performance.

3. Split the Dataset (2 marks)

Split the dataset into training (80%) and testing (20%) sets using random_state=45.

4. Linear Regression Implementation (30 marks)

A Python implementation of Linear Regression using:

Mean Squared Error (MSE) as the loss function.

Gradient Descent for optimization.

Code is implemented without external libraries (except numpy and pandas).

5. Loss vs Epoch Plot (3 marks)

Plot the convergence of the loss function over training epochs.

6. Prediction Example (2 marks)

Given input data:

Hours of study: 7

Previous score: 95

Extracurricular Activities: Yes

Duration of Sleep: 7

Sample Question Papers Practiced: 6

Predict the student’s performance using the trained model.

7. Model Evaluation (5 marks)

Evaluate the trained model using the following metrics:

Mean Squared Error (MSE)

R2 Score

Task 2: Regression Using Libraries

1. Implementation

Train a regression model using scikit-learn’s LinearRegression class.

2. Comparison

Analyze and compare the results of the scratch implementation vs the library-based implementation.

Discuss possible improvements to the scratch implementation:

Feature scaling.

Tuning learning rate.

Increasing training epochs.

Report

A compact and clear report is included in this repository, summarizing:

Key steps of the implementation.

Observations from EDA.

Performance metrics.

Comparisons and conclusions.

File Structure

linear_regression_scratch.ipynb: Implementation of Linear Regression from scratch.

linear_regression_library.ipynb: Regression using libraries.

report.pdf: Detailed report.

README.md: This file.

Instructions to Run

Clone the repository:

git clone <repository-link>

Open the notebooks in Google Colab or Jupyter Notebook.

Install required dependencies:

pip install pandas numpy matplotlib scikit-learn

Run the notebooks sequentially.

Sample Prediction

Using the trained scratch model, the predicted performance for the sample data is provided in the output of linear_regression_scratch.ipynb.


