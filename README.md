# Loan status prediction using R programming


<p align="center">
![image](https://github.com/user-attachments/assets/1ee91cc3-f4c1-432d-8721-f1d6569280d5)

</p>




## Methodology:
In the loan prediction system I did two types of analysis depending on the data columns. 

### Feature Extraction
In tackling the classification problem, I employed BestGLM to meticulously explore potential predictors and identify the most effective ones. This tool facilitated the comprehensive selection of influential features, optimizing the model's performance in the classification context.

For the loan amount prediction task, regsubsets was utilized to pinpoint the optimal set of features. The objective was to identify a subset of features that significantly contributed to accurate loan amount predictions. Metrics such as Adjusted R squared, Mallow Cp, and Bayesian Information Criterion (BIC) scores guided the evaluation of different feature subsets. This meticulous selection process ensured that only the most meaningful features were retained, enhancing the predictive accuracy and generalization capabilities of the loan amount prediction model.

### Classification
The approval or rejection status of a loan is predicted through the application of non-parametric classification algorithms such as Random Forest Classifier, Decision Tree, and K-Nearest Neighbors (KNN). Additionally, logistic regression was employed to analyze the outcomes. Among these, the Random Forest Classifier demonstrated the most favorable performance, achieving a remarkable **98.32%** Area Under the Curve (AUC) score.


### Prediction

The determination of the loan amount borrowed by the applicant is conducted through the application of linear regression. This model has yielded favorable outcomes, demonstrating an adjusted R^2 value of **86.2%**.
