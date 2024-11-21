Introduction<br>
This project focuses on loan approval prediction using structured data from a Kaggle competition. The objective is to classify loan applications as approved or not based on features such as personal financial history, loan details, and credit information. This problem involves imbalanced data and complex feature interactions, necessitating careful preprocessing and robust modeling approaches.

Problem<br>
The main challenges encountered during the project included:

Data Imbalance: The target variable, loan_status, was highly imbalanced, with significantly more approved loans than rejected ones. This required resampling techniques to balance the dataset.
Feature Engineering: Converting categorical features like loan_intent and loan_grade into numerical representations without losing information was crucial.
Model Selection: Identifying a model capable of handling a mix of numerical and categorical data efficiently while balancing accuracy and computational cost.
Approach and Solutions
Exploratory Data Analysis (EDA): Conducted detailed analysis of feature distributions, correlations, and outliers. Visualized key trends such as income versus loan amount and interest rate distributions.
Data Preprocessing:
Addressed missing values and encoded categorical variables using one-hot encoding.
Resampled the dataset to handle the class imbalance, ensuring balanced representation of approved and rejected loans.
Feature Selection: Selected key features based on domain knowledge and exploratory findings to improve model interpretability.
Modeling:
Used XGBoost, a gradient-boosting algorithm, as the primary model due to its ability to handle complex feature interactions and imbalanced datasets.
Fine-tuned hyperparameters using a random search approach for optimal performance.
Evaluation: Assessed the model's accuracy and precision, achieving a strong balance between predictive performance and efficiency.
