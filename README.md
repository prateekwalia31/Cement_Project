# Cement_Project

## Description

This project deals with a comparative analysis of different Machine Learning (ML) techniques for predicting the compressive strength, which is its ability to resist cracks when a compressive force is applied. The 28-day compressive strength is one of the most important properties of cement for building infrastructure and accurately predicting this property is vital in many construction projects.

## Dataset and EDA

- The dataset used in this project contains various features such as cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, fine aggregate, age, and the target variable, compressive strength. The datset used is avavialble in the repsoitory as a CSV file named _concrete.csv_.

- Histogram distributions and box plots were used to visualize the distribution and outliers for each feature.

- Pairplots and a correlation heatmap were also created to explore the relationships and correlations between various features.

## Feature Scaling and Engineering

- Outliers in the dataset were removed using a function that replaces extreme values with NaN.
  
- Zero values were replaced with the mean of each feature.
 
- The data was then scaled using normalization.

## Data Splitting

- The preprocessed data was split into training, validation, and testing data sets. 70% of the data was used for training, while 15% each was allocated for validation and testing.


## Model Development and Evaluation

For predicting cement compressive strength, three regression models were evaluated (KNN Regressor,  Random Forest Regressor, andExtreme Gradient Boosting (XGB)) using different metrics including R-squared, RMSE, MSE, and MAE values. An ensemble model was also built by combining the KNN, Random Forest, and XGB models using a voting regressor.

## Results and Conclusion

Each model was tested using the evaluation metrics R-squared score, RMSE, MSE, and MAE values. To evaluate the performance of each model based on the graphically, a bar chart was created for the four metrics. The Colab Notebook contains the project's code and findings. Please refer to the notebook for more information and step-by-step details on data preprocessing, model development, and evaluation.

