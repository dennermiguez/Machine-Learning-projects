# Assessing customer churn using machine learning
The telecommunications (telecom) sector in India is rapidly changing, with more and more telecom businesses being created and many customers deciding to switch between providers. "Churn" refers to the process where customers or subscribers stop using a company's services or products. Understanding the factors that influence keeping a customer as a client in predicting churn is crucial for telecom companies to enhance their service quality and customer satisfaction. As the data scientist on this project, you aim to explore the intricate dynamics of customer behavior and demographics in the Indian telecom sector in predicting customer churn, utilizing two comprehensive datasets from four major telecom partners: Airtel, Reliance Jio, Vodafone, and BSNL:
- Load the two CSV files into separate DataFrames. Merge them into a DataFrame named churn_df. Calculate and print churn rate, and identify the categorical variables in churn_df.
- Convert categorical features in churn_df into features_scaled
-  Perform feature scaling separating the appropriate features and scale them
-  Split the processed data into training and testing sets
-  Train Logistic Regression and Random Forest Classifier models
-  Assess the models on test data. Assign the model's name with higher accuracy
