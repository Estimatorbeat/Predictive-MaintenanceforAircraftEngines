# Maintenance for Aircraft Engines Using Machine Learning

![R](https://github.com/Estimatorbeat/Predictive-MaintenanceforAircraftEngines/assets/154437491/ebecad1e-a88d-49dc-a2a1-25a7de18915e)


## Project Overview
The "Maintenance of Aircraft Engiines using machine Learning"  project aims to develop an intelligent system capable of identifying Aircraft engine failure. By leveraging advanced analytics and machine learning techniques on aircraft data, to accurately predict the likelihood of a aircraft having engine failure, ensuring the safety, reliability, and efficiency of air travel.

## Project Objective
The primary objective of this project is to build and train a robust machine learning model that can accurately detect if the aircraft engine will fail or not. The model will be designed to classify aircraft engine.

## Data Sources
The dataset used in this project was provided by 10Alytics. The data set contains aircraft historical data from various engines including Pressure, Temperature, Rotational Speed, Vibration Level and other relevant information.  

## Data Preprocessing
Before feeding the data into the machine learning model, extensive data processing was performed. This include handling missing value, handling outliers, scaling features and addressing class imbalance(if applicable). Additionally, feature engineering techniques were applied to extract relevant information from the data.

## Machine Learning Model
The aircraft engine maintenance prediction model is built using a supervised marchine learning approach. Training and test data was spilt 80:20. Several classification algorithm were experimented with, inclding but not limited to:
- **Decisipon Trees**
- **Random Forest**
- **Logistic Regression**
- **Support Vector Machines (SVM)**

After Extensive experimentation and hyperparameter tuning, the final machine learning was selected based on its performance and generalization capabilities.

## Evaluation Metrics
To assess the performance of the machine learniung model, the following evaluation metrics were used:

- Precision: The proportion of correctly identified engine failed among all engine failure classified as failed.
- Recall: The proportion of correctly identified engine failed among all actual engine failed.
- F1-score: The harmonic mean of precision and recall, providing a balance metric for model evaluation.
- Accuracy: Accuracy measures the overall correctness of the model's predictions.(both engine failed and engine ok).

## Key Insights
- The purpose of this project is to predict aircraft engine failure.
- The best model that predicts with less error is to be chosen, subjecting them to the diiferent metrics including k-foldcross validation(accuracy, precision and recall).
- The confusion matrix displays the error value for each model in terms of False Positive (Where the model predicts an aircraft engine to fail when they actually didn't - Precision) and False Negative (Where the model predicts an aircraft engine to be ok and it wasn't - Recall).
- After Evaluation, the model with the highest recall will be deployed. Recall is the most relevant matrix for evaluation in this aircraft maintenance problem. This is because, the effort of the error (Recall) on the aircraft engine if not addressed will be massive compared to that of precision.


## Conclusion
The 'Maintenance for Aircraft Engines Using Machine Learning' project showcases the effectiveness of machine learning algorithms in safeguarding aircraft engine against engine failure. By accurately identifying and preventing engine fail, this model enhances the security and assurance of aircraft engine . DecisionTrees: For this aircraft maintenance problem, Recall score is of more relevant and DecisionTrees has highest recall score compared to other models. hence, It should be depolyed by Aviation Company for faceing the pressing need to detect aircrafe engine failure, as it has 94% Recall and Accuracy is 86%.
