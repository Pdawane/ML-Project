# ML-Project
Description:
This project aims to predict the responses of CAR-PUF (Challenge-Response Pair - Physically Unclonable Function) by mapping 32-bit challenges to feature vectors using various linear models in scikit-learn. The work focuses on developing an accurate prediction mechanism by leveraging advanced feature engineering techniques and custom implementations of machine learning models.

Key Features:
Challenge-Response Mapping: Implemented a pipeline that converts 32-bit challenges into feature vectors suitable for prediction models.

Custom SVM Classifier: Developed a custom Support Vector Machine (SVM) classifier that integrates advanced feature engineering techniques, including the Khatri-Rao product and cumulative product transformations, to enhance model performance.

Model Accuracy: Demonstrated high prediction accuracy using LinearSVC and LogisticRegression for breaking CAR-PUFs, showcasing the effectiveness of the chosen linear models.

Tools and Technologies:
Python Programming: Used Python for implementing the models and feature engineering techniques.
scikit-learn: Leveraged scikit-learn for building and evaluating the linear models.
Feature Engineering: Applied Khatri-Rao and cumulative product transformations to improve model input quality.
Outcome:
The project successfully predicts CAR-PUF responses, demonstrating the capability of linear models in breaking CAR-PUFs when combined with robust feature engineering techniques.
