# Spam Mail Prediction using Machine Learning

## Project Description

The Spam Mail Prediction project utilizes machine learning techniques to classify emails as either "spam" or "ham" (non-spam). This project is designed to help users filter unwanted emails, enhancing their email management experience.

## Key Features

- **Data Collection**: The project begins with the collection of email data, which is stored in a CSV file. The dataset contains two columns: "Category" (indicating whether the email is spam or ham) and "Message" (the content of the email).

- **Data Preprocessing**: The raw email data undergoes preprocessing to handle missing values and prepare it for analysis. This includes replacing null values and encoding the categories into numerical values for model training.

- **Feature Extraction**: The project employs the Term Frequency-Inverse Document Frequency (TF-IDF) vectorization technique to convert the text data into numerical feature vectors. This transformation is crucial for the machine learning model to understand and process the text data effectively.

- **Model Training**: A Logistic Regression model is trained on the processed data. The model learns to distinguish between spam and ham emails based on the features extracted from the email content.

- **Model Evaluation**: The trained model is evaluated using accuracy metrics on both training and test datasets. This evaluation helps in assessing the model's performance and its ability to generalize to unseen data.

- **Predictive System**: The project includes a predictive system that allows users to input new email messages and receive predictions on whether the email is spam or ham. This feature provides a practical application of the trained model.

## Conclusion

This project demonstrates the application of machine learning in natural language processing, specifically in the context of email classification. By leveraging data preprocessing, feature extraction, and model training, the Spam Mail Prediction project aims to provide an effective solution for managing spam emails.
