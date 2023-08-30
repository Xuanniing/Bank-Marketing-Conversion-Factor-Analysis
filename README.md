# Bank Marketing Campaign Engagement Factor Analysis
## Problem Statement
In the realm of marketing, understanding the factors that influence customer behaviour is pivotal for crafting effective strategies. This analysis delves into the data derived from a bank's marketing campaign to discern the determinants that significantly impact the success of customer conversions. The primary goal is to identify the specific characteristics that define the audience with a higher likelihood of conversion. The insights gained can be harnessed to develop more focused and tailored marketing strategies, ensuring a more efficient allocation of resources and a more precise targeting of the audience.
## Steps to solve the problem
**Tools / Libraries:** Python, Pandas, Matplotlib (Visualization), Sklearn (Machine Learning)

**Dataset:** [UCI Machine Learning repository](http://mlr.cs.umass.edu/ml/datasets/Bank+Marketing)

**Analysis Performed:** Logistic Regression, Random Forest

  ### Data Understanding and Data Preprocessing
  ### Model Selection
Random Forests has the ability to handle complex relationships and interactions within the data, making them effective in capturing non-linear patterns that might exist in the features affecting customer conversions. We can also gain insights from feature importance scores provided by the model to uncover attributes’ contributions to conversion.

Logistic Regression is well-suited for binary classification tasks like this. Interpreting the relationships between the independent variables and the dependent variable can provide coefficients that indicate the direction and magnitude of each feature's influence on the conversion outcome. 

The sign of the coefficient reveals whether the relationship is positive or negative, while Random Forests provide robustness in capturing complex relationships. By employing these two distinct models, we aim to attain a comprehensive understanding of the factors driving customer conversions, enabling us to formulate effective marketing strategies based on data-driven insights.
  ### Hyperparameter Tuning
  use randomized search approach
  ### Model Training and Evaluation
  ### Adjust Hyperparameters 
  ### Feature Importance (interpretation)
  ### Logistic Regression for Feature Importance Validation

 ## Conclusion
 The analysis revealed several variables that consistently demonstrated strong correlations with conversion outcomes across both Random Forest and Logistic Regression models. 
 These variables include: Duration, Pdays, Balance, Housing Status, Loan Status, Marital_Married, job_blue_collar, and education_primary.
