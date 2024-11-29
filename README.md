# diabetes predictor web application
Developed a diabetes prediction model using Random Forest, deployed with Flask, achieving 85% accuracy to assist in early diagnosis.

The diabetes prediction model works by using a dataset of medical attributes (such as age, BMI, glucose levels, and family history) to predict whether a person is at risk of diabetes. Here's a brief breakdown of its working:

Data Collection: The model is trained on a dataset containing various health metrics, with the target variable being whether the person has diabetes or not.

Preprocessing: The data is cleaned by handling missing values, encoding categorical variables, and normalizing numerical values to ensure better model performance.

Model Training: A Random Forest Classifier is used, which builds multiple decision trees and makes predictions based on the majority vote of these trees. The model learns the patterns in the data to classify individuals as diabetic or non-diabetic.

Evaluation: The model is evaluated using accuracy, precision, recall, and F1 score metrics to determine how well it predicts diabetes.

Deployment: The model is deployed using Flask, creating a web application where users input their health data, and the model predicts the likelihood of diabetes, offering early diagnostic assistance.

The Random Forest model provides an efficient and interpretable way to predict diabetes risk based on the given health parameters.
