House Price Prediction with the Ames Housing Dataset
Purpose of the project
The primary objective of this project was to develop and evaluate regression models capable of accurately predicting house sale prices based on various features of residential properties in Ames, Iowa. 
In addition to predictive modeling, the project involved thorough data cleaning, feature engineering, and exploratory analysis to uncover the most influential factors affecting home values. 
The end goal was to identify the most effective model and gain insights into the real estate market dynamics in Ames.

Data
Source: https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset?select=AmesHousing.csv
Scope: 2,930 observations and 79 explanatory variables
Format: Tabular, mixed types (numerical and categorical)

Technologies
Python – core programming language for data science workflow
Pandas – data cleaning, transformation, and encoding
Matplotlib & Seaborn – visualization of distributions, relationships, and correlations
Scikit-learn – model building, evaluation, and hyperparameter tuning
XGBoost – gradient boosting regressor for high-performance modeling
Jupyter Notebook – analysis environment for code, visualizations, and narrative

Methods
Data cleaning: Removal of columns with excessive missing or zero values, imputation, and consolidation of related features
Feature engineering: Transformation of year columns into age variables, class grouping of categorical features, logarithmic scaling of skewed variables
Exploratory analysis: Correlation matrix, distribution analysis, and scatter plots for SalePrice
Modeling: Comparison of Linear Regression, Lasso, Random Forest, KNN, and XGBoost using GridSearchCV with cross-validation
Evaluation: R^2 score and RMSE on the original price scale

Results
Best model: XGBoost Regressor
R² score: 0.8936
RMSE: ~$27,627 on test set
Key predictors: Overall quality, ground living area, garage size, total basement size
