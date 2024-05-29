# ClassifierPipeline
This code aims to automatically process the data, and find the best classifier model to predict the data from the commonly used ones.

# To-do list:
Data Processing:
EDA
  Data Summary, Visualization, Correlation Matrix
  
Advanced Missing Data Handling
  Imputation Strategies: Use mean, median, mode, or advanced methods like K-Nearest Neighbors (KNN) imputation.
  
?Encoding Categorical DataTarget Encoding:
  Encode categorical variables based on the target variable.
  One-Hot Encoding: Use one-hot encoding for nominal categorical features.
  Ordinal Encoding: Use ordinal encoding for ordinal categorical features.

Outlier Detection and Handling
  Outlier Detection: Use statistical methods (e.g., IQR, Z-score) or machine learning methods (e.g., isolation forests) to detect outliers.
  Outlier Treatment: Decide whether to remove, cap, or transform outliers.

Feature Scaling
  Consider other scalers like MinMaxScaler or RobustScaler if StandardScaler is not suitable. Scaler settings.
  
Handling Imbalanced Data
  Resampling Methods: Use oversampling (e.g., SMOTE) or undersampling techniques.
  Class Weights: Assign weights to classes in the loss function.

Pipeline Integration
  Pipeline Object: Use sklearn.pipeline.Pipeline to chain together preprocessing and modeling steps.
