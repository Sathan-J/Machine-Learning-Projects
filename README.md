#Credit Score Categorisation

Financial institutions categorize their customers' credit scores into three main groups:
 1. Excellent
 2. Average
 3. Poor
  
Individuals with an excellent credit score typically have access to loans from various banks and financial organizations. To conduct Credit Score Categorization effectively, a dataset containing labeled credit scores based on customers' credit histories is essential.

I've discovered an optimal dataset for this purpose, accurately labeled according to the credit histories of credit card customers. (Dataset - https://statso.io/credit-score-classification-case-study/)

In this Understanding the significance of the target variable, which in this case is the **"Credit_Score" **column, is crucial. It serves as the focal point for the model's predictions and influences the entire modeling process.

The choice of the **RandomForestClassifier** algorithm suggests a decision here to leverage the strengths of ensemble learning techniques. RandomForestClassifier is known for its robustness, versatility, and ability to handle complex datasets with high dimensionality.
