# regression-house_price_prediction
Analysis on Housing Dataset (Kaggle), EDA, Feature Engineering, PCA Dimension Reduction, and Regression Modelling to predict House Price

Final Project SDSC2001 Python for Data Science - Grade: A+
Lecturer: Dr. LI Xinyue
City University of Hong Kong

## Data Preprocessing
- Missing Values
- Outliers

## Exploratory Data Analysis (seaborn and matplotlib)
- Visualizations: Heatmap, Pairwise Plot, Violin Plot Distribution Plot, Box Plot
- Initial exploration of the dataset for features selection

## Feature Engineering
- Select important features that have effect to target variable Price
- One-hot Encoding for nominal variables
- Ordinal Encoding for ordinal variables
- Scaling using Standard Scaler

## Dimension Reduction
- Principal Component Analysis (PCA), finding n component using cumulative sum of variance ratio to reach 95%

## Regression Models
- 5-Fold Cross Validation, metric = RMSE
- Initial model exploration using LazyPredict
- Models: Linear Regression, SVM Regressor, LGBM Regressor

## Characteristics Analysis on Bad Predictions
- Distribution Plots of features to high error count of prediction to target values
