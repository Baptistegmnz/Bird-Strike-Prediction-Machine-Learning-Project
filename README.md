# Bird-Strike-Prediction-Machine-Learning-Project
Bird strikes pose a significant risk to aviation safety, particularly during takeoff and landing. With the frequency of these incidents rising, understanding the underlying risk factors has become essential. This project focuses on the study of collisions between aircraft and wildlife, using machine learning and large-scale data analysis to predict whether an incident results in physical damage. By combining predictive modeling with historical data, this study aims to provide insights that can help enhance aviation safety and risk management.

## Repository content

* Project_code.ipynb: Jupyter Notebook containing the full code. Throughout the file, steps and results are commented to provide a clear overall understanding of the program and the analytical approach.
* bird_strikes.csv: Dataset used for training and testing the models.

## Methodology

The project follows several key steps:
1. Data Cleaning: Removing irrelevant variables and handling missing values.
2. Preprocessing: Feature encoding, scaling, and logarithmic transformations.
3. Dimensionality Reduction: Using Principal Component Analysis (PCA).
4. Evaluation: Comparing several algorithms to identify the most effective one.

## Models tested

The following algorithms were implemented and compared:
* Logistic Regression (Baseline)
* Random Forest
* Gradient Boosting
* PCA combined with Logistic Regression

## Results

The Gradient Boosting model shows the best overall robustness. However, the approach combining PCA and Logistic Regression achieved the highest recall, which is crucial in a safety context to detect as many actual damage cases as possible.

## Installation and prerequisites

To run the notebook, the following Python libraries are required:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
