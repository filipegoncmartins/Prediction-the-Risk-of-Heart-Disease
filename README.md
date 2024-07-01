
# Prediction the Risk of Heart Disease

This project aims to predict the risk of heart disease in individuals based on various health metrics and demographic information. Using machine learning models, we strive to build a predictive model that can aid in early detection and prevention of heart disease.

![aaa](https://github.com/filipegoncmartins/Prediction-the-Risk-of-Heart-Disease/assets/148718210/d3ef570e-02bf-4743-b336-bb5f2ed3c8ff)


## Problem to be Solved

Heart disease is a leading cause of death worldwide, and early detection is crucial for effective treatment and prevention. By leveraging data from health surveys, we aim to develop a model that can predict the likelihood of heart disease, thereby providing valuable insights for healthcare professionals and patients.

## Dataset Information

The dataset used in this project contains health-related information for a large number of individuals. Below are the columns included in the dataset:

* HeartDisease:  indicates whether respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction. Possible values are Yes and No.
* BMI: Body Mass Index, a numerical value.
* Smoking: Indicates whether the individual smokes. Possible values are Yes and No.
* AlcoholDrinking: Indicates whether the individual consumes alcohol. Possible values are Yes and No.
* Stroke: Indicates a history of stroke. Possible values are Yes and No.
* PhysicalHealth: Number of days with physical health issues in the past month. This is a numerical value ranging from 0 to 30.
* MentalHealth: Number of days with mental health issues in the past month. This is a numerical value ranging from 0 to 30.
* DiffWalking: Indicates difficulty in walking or climbing stairs. Possible values are Yes and No.
* Sex: Gender of the individual. Possible values are Male and Female.
* AgeCategory: Age group of the individual. Possible values are 18-24, 25-29, 30-34, 35-39, 40-44, 45-49, 50-54, 55-59, 60-64, 65-69, 70-74, 75-79, and 80 or older.
* Race: Race or ethnicity of the individual. Possible values are White, Black, Hispanic, Asian, American Indian/Alaskan Native, and Other.
* Diabetic: Indicates whether the individual has diabetes. Possible values are Yes, No, Borderline diabetes, and Yes (during pregnancy).
* PhysicalActivity: Indicates engagement in physical activities or exercises. Possible values are Yes and No.
* GenHealth: General health status. Possible values are Excellent, Very good, Good, Fair, and Poor.
* SleepTime: Average hours of sleep per night. This is a numerical value ranging from 0 to 24.
* Asthma: Indicates whether the individual has asthma. Possible values are Yes and No.
* KidneyDisease: Indicates whether the individual has kidney disease. Possible values are Yes and No.
* SkinCancer: Indicates whether the individual has skin cancer. Possible values are Yes and No.
* HeartDisease_FamilyHistory: Indicates a family history of heart disease. Possible values are Yes and No.
* State: U.S. state where the individual resides. Possible values are state abbreviations such as OH, ND, NC, NY.


## Steps followed 

### [1]  Data Cleaning and Preprocessing:

* Handled missing values and categorical variables.
* Scaled numerical features to ensure equal contribution to the model.

### [2] Exploratory Data Analysis (EDA):
    
* Examined the distribution of various features.
* Investigated correlations between features and the target variable, HeartDisease.
* Visualized the distributions and relationships using plots and graphs.
    
### [3] Feature Selection:

* Identified the most important features influencing the target variable using techniques like correlation analysis.

### [4] Model Development:

* Implemented various machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, and K-Nearest Neighbors.
* Performed hyperparameter tuning to optimize model performance.

### [5] Model Evaluation:

* Assessed model performance using metrics such as ROC AUC Score.
* Plotted ROC Curves to compare the models.

### [6] Insights and Conclusions:

* Gradient Boosting Classifier achieved the highest ROC AUC Score, indicating the best performance in predicting heart disease.
* Logistic Regression and Random Forest also performed well, while K-Nearest Neighbors had comparatively lower performance.

## Insights

- Gradient Boosting: Achieved the highest ROC AUC Score, making it the best model for this dataset.
- Feature Importance: Key features influencing heart disease prediction include DiffWalking, Stroke, Diabetic, and GenHealth.
- Model Performance: Logistic Regression and Random Forest provided robust predictions with high accuracy, while K-Nearest Neighbors showed lower predictive power.
- Data Insights: Age, general health, and presence of other medical conditions like stroke and diabetes are significant indicators of heart disease.

## Conclusion

This project demonstrates the application of various machine learning models to predict heart disease using health survey data. The insights gained can be valuable for healthcare professionals in early detection and intervention, ultimately contributing to better patient outcomes.
