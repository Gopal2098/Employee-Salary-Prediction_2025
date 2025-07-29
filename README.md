# Employee-Salary-Prediction_2025
Employee Salary Prediction Using Machine Learning

This is a capstone project for the IBM internship program that demonstrates an end-to-end machine learning workflow. The goal of this project is to predict whether an individual's annual income is greater than $50,000 or less than or equal to $50,000 based on socio-economic data from the 1994 US Census.

The project achieves a final accuracy of 87.19% using a tuned Gradient Boosting Classifier.
Features

    Data Cleaning: Handles missing values and removes irrelevant categories from the dataset.

    Data Preprocessing: Uses scikit-learn Pipelines to robustly scale numerical data and encode categorical data.

    Model Training: Employs a powerful GradientBoostingClassifier.

    Hyperparameter Tuning: Uses GridSearchCV to find the optimal settings for the model, maximizing its predictive accuracy.

    Model Persistence: The final, tuned model is saved to a final_salary_prediction_model.pkl file so it can be easily loaded and used for future predictions.

How to Use This Project
Prerequisites

    Python 3.x

    The required libraries can be installed via pip:

    pip install pandas numpy scikit-learn joblib matplotlib seaborn

Project Structure

    Emp.Salary.Prediction Pro final.ipynb: The main Jupyter Notebook containing all the steps from data cleaning to model training and saving.

    Emp.Salary.Prediction Pro final.ipynb: A separate Python script available in downside to load the saved model and make predictions on new data.

    adult 3.csv: The raw dataset used for training.

    final_salary_prediction_model.pkl: The final, saved machine learning model.

    README.md: This file.

Running the Project

    Train the Model:

        Open and run all the cells in the Emp.Salary.Prediction Pro final.ipynb notebook.

        This will perform the data cleaning, train the model, and create the final_salary_prediction_model.pkl file.

    Make a Prediction:

        You can modify the new_employee_data dictionary inside the Emp.Salary.Prediction Pro final.ipynb script with new values.

        Run the script from your terminal to get an instant salary prediction:

        python Emp.Salary.Prediction Pro final.ipynb

