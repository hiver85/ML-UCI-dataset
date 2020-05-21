# Machine-Learning
- This is my personal project on Machine learning. This folder inclus 3 project: 
  - **Visualize and predict UCI datasets** using different machine learning algorithm to compare their efficiency. This my first machine learning project from the master course of Innovation information system
  - **Kaggle house price prediction:** This is my second project from the master course. This is also a challenging task. The data is noisy with a lot of null values, outliers and not easy to interpret. Some technique I used:
    - Data exploration and cleaning: visualization and statistics infos (skewness, outlier, distribution, quantile, groupby, correlation, fillna, LabelEncoder, min-max scaler, log scaler, one hot encoder, PCA)
    - Fit the model: In this project, the aim is to compare different models to find out the most suitable one for the dataset
      - Choose some model to apply: Since it's a regression supervised problem, some models have chosen and then compare their effectiveness.
      - Some models chosen: Random Forest, Boost (GradientBoostingRegressor, Xboost), LightGBM, Elastic Net Regression, Ridge
      - To avoid overfitting, cross-validation has been included
      - After all, choose 3 best model (LightGBM, Elastic Net and GradientBoostingRegressor) to create an average model
    - Extract the result to submission file
    
  - **Analyze the depression dataset:** This is a personal project to predict if a person is depressed. The difficult of this dataset is imbalance and a lot of redundance feature. I good features aren't well selected. No good result can be atteint
    - Some technical applied to this dataset is: Data exploration and cleaning, consider the correlation, use PCA to reduce the dimension and using SMOTE to reduce the imbalance
    - Model: There are 2 labels, so logistic regression and LightGBM are applied and compared. The result show that Logistic regression work better than LightGBM
