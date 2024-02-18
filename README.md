# credit_risk_classification
This Jupyter notebook presents a comprehensive analysis and machine learning model for credit risk classification. The primary goal is to accurately classify loan applications as either a high risk or low risk of default. The analysis is crucial for financial institutions to make informed lending decisions.

Key Steps
Data Preparation: The notebook begins with loading the lending_data.csv file into a Pandas DataFrame. This step is crucial for understanding the structure and content of the dataset, which includes various financial indicators related to loan applications.

Feature Selection and Label Creation: The dataset's "loan_status" column is used to create labels (y), while the remaining columns are used as features (X). This separation is fundamental for the machine learning model to learn from the dataset.

Model Training and Evaluation:

A logistic regression model is trained using the separated features and labels.
The model's performance is evaluated using metrics such as accuracy score, confusion matrix, and classification report to understand its effectiveness in predicting credit risk.
Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Scikit-learn: For machine learning model training, testing, and evaluation.
Conclusion
This notebook provides a detailed approach to classifying credit risks using logistic regression. It demonstrates the process of data preparation, model training, and evaluation, offering insights into the predictive capabilities of the model regarding loan application risks.