# Customer Churn Prediction

## 📌 Project Overview

This project focuses on predicting whether a customer is likely to churn or not using Machine Learning algorithms.

The project uses customer information and applies different Machine Learning classification algorithms to predict customer churn.

## 🎯 Objective

The main objective of this project is to identify customers who are likely to leave a service and help businesses take appropriate customer-retention actions.

## 📂 Dataset

The project uses the **Churn Modelling dataset**.

The following columns were removed during preprocessing:

* CustomerId
* RowNumber
* Surname

The target variable used for prediction is **Exited**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🤖 Machine Learning Algorithms Used

The following classification algorithms were implemented and compared:

* Logistic Regression
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Naive Bayes
* XGBoost

## 🔄 Project Workflow

1. Load the customer churn dataset
2. Explore and understand the dataset
3. Preprocess the data
4. Handle categorical variables
5. Remove unnecessary columns
6. Define features and target variable
7. Split the dataset into training and testing data
8. Apply feature scaling
9. Train different Machine Learning models
10. Compare model performance
11. Select the best-performing model
12. Test the model on a new customer record

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## 🏆 Best Model

Among the tested models, **Random Forest** achieved the best overall performance with:

* **Accuracy:** 86.60%
* **F1 Score:** 58.39%

The final model was also tested on a new customer record and predicted that the customer was **not likely to churn**.

## 💡 Conclusion

This project demonstrates how Machine Learning can be used to predict customer churn.

By identifying customers who are likely to leave a service, businesses can take appropriate customer-retention actions and improve customer satisfaction.

## 📁 Project Files

* `Churn(2).ipynb` – Jupyter Notebook containing data preprocessing, model training, evaluation and prediction.
* `Churn_Modelling.csv` – Dataset used for the project.
* `xgboost_final_model.pkl` – Saved Machine Learning model.
* `README.md` – Project documentation.
