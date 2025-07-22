Employee Salary Prediction using GradientBoostingClassifier
This project focuses on predicting whether an employee's salary is greater than 50K or less than or equal to 50K using machine learning. A GradientBoostingClassifier model was developed to classify salaries based on features such as age, education, work class, and occupation.

Project Workflow:

Data Preprocessing:
Handling missing values
Encoding categorical variables
Feature scaling using StandardScaler

Model Building:
Algorithm Used: GradientBoostingClassifier (from scikit-learn)
Training and Testing the Model
Model Evaluation using accuracy score and classification report

Model Deployment:
Model saved usin Pickle (model.pkl)
Ready for deployment in real-time applications

Libraries Used:
pandas
numpy
scikit-learn
pickle

How to Use:
Clone the repository
Load the ESP.ipynb notebook
Train or load the pre-trained model (model.pkl)
Input employee data and predict salary class (>50K or <=50K)

Future Improvements:
Integrate web API using Flask/Django
Use XGBoost or LightGBM for comparison
Develop a user-friendly frontend for predictions
Add explainability with SHAP or LIME

Dataset Source
UCI Machine Learning Repository: Adult Income Dataset 
