# Heart-Disease-Prediction
This project uses machine learning classification techniques to predict the likelihood of heart disease in individuals based on medical data. The dataset contains 303 records with 13 features such as age, cholesterol levels, blood pressure, and other health-related metrics. The target variable is binary: 1 indicates the presence of heart disease, while 0 represents a healthy individual.

Steps Involved:
Data Collection: The dataset, containing patient information, is sourced from a public repository. It includes key health indicators that can help identify the risk of heart disease.

Data Preprocessing:
            Load dataset.
Train-Test Split: The dataset is divided into training (70%) and testing (30%) subsets. Stratified sampling ensures that the distribution of the target variable (heart disease vs. no disease) is consistent across both sets.

Model Training: A Logistic Regression classifier is chosen due to its effectiveness in binary classification tasks. The model is trained on the training set to learn patterns that distinguish between healthy individuals and those at risk of heart disease.

Model Evaluation: The model’s performance is evaluated using accuracy, precision, recall, and F1-score to ensure it can predict heart disease accurately.

Prediction: After training, the model can predict whether new patients are at risk of heart disease based on their health attributes.
