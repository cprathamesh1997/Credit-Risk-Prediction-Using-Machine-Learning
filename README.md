# Credit-Risk-Prediction-Using-Machine-Learning

### *The Credit Risk Prediction project aimed to develop a robust machine learning model to predict loan status based on simulated credit bureau data.The dataset included features such as age, income, home ownership, loan amount, and historical credit information. The primary goal was to assess creditworthiness and differentiate between default and non-default cases.*

## 1.Data Exploration:

### a.Explored the credit risk dataset, understanding the features, and the target variable.
### b.Visualized the distribution of features, correlations, and key statistics.
### c.Identified potential issues such as missing values and outliers.

## 2.Feature Engineering:

### a.Engineered new features such as age groups, income groups, and loan amount groups.
### b.Created ratios to capture relationships between features, such as loan-to-income and interest rate-to-loan amount ratios.

## 3.Data Preprocessing:

### a.Handled missing values and dropped unnecessary columns.
### b.Applied one-hot encoding to categorical variables.
### c.Scaled numerical features using StandardScaler.

## 4.Model Training and Evaluation:

### a.Trained multiple machine learning models, including SVM, KNN, XGBoost, CatBoost, and LightGBM.
### b.Evaluated models using metrics like accuracy, precision, recall, and specificity.
### c.Identified CatBoost Classifier as the best-performing model.

## 5.Hyperparameter Tuning:

### a.Used Bayesian Optimization to fine-tune hyperparameters for the LightGBM model.
### b.Achieved optimized hyperparameters for better model performance.

## 6.Ensemble Model:

### a.Implemented a VotingClassifier ensemble with KNN, CatBoost, and LightGBM models.
### b.Evaluated the ensemble model's performance and achieved improved results.

## 7.Feature Importance:

### a.Explored feature importance using RandomForestRegressor to understand the impact of different features on the model's predictions.
### b.Visualized feature importance for better interpretability.

## 8.AutoML with PyCaret:

## a.Utilized PyCaret to perform AutoML, comparing various machine learning models and selecting the best-performing one.Streamlined the model comparison and selection process.

# Conclusion:

## Concluded with a summary of the best-performing model (CatBoost Classifier) and its evaluation metrics.Provided insights into feature importance and potential areas for further exploration.In conclusion, the Credit Risk Prediction project successfully developed and implemented machine learning models to predict loan status. The insights gained from the analysis contribute to a better understanding of credit risk factors, and the models provide a foundation for future enhancements and refinements.







