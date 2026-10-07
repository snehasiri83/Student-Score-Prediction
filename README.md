# Student Score Prediction 📊

## 📌 Project Overview

This project uses **Machine Learning** to predict a student's exam score based on the number of hours they studied.

A **Linear Regression** model is used to learn the relationship between study hours and exam scores.

## 🎯 Objective

The objectives of this project are:

* Understand the basic Machine Learning workflow.
* Analyze the relationship between study hours and exam scores.
* Train a Linear Regression model.
* Predict exam scores for test data.
* Evaluate the model using different performance metrics.
* Predict the score of a new student based on study hours.

## 📂 Dataset

The dataset contains two main columns:

| Column  | Description                          |
| ------- | ------------------------------------ |
| `Hours` | Number of hours studied by a student |
| `Score` | Exam score obtained by the student   |

`Hours` is used as the input feature, while `Score` is the target variable.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 🔄 Project Workflow

1. Import libraries
2. Load the dataset
3. Explore the dataset
4. Visualize the data
5. Split the dataset into training and testing sets
6. Create the Linear Regression model
7. Train the model
8. Predict scores for test data
9. Evaluate the model
10. Visualize the regression results
11. Compare actual and predicted scores
12. Predict the score of a new student
13. Draw the final conclusion

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression is used to predict a numerical value based on the relationship between an input feature and a target variable.

In this project:

**Study Hours → Exam Score**

The model learns this relationship from the training data and uses it to make predictions.

## 📊 Model Evaluation

The model is evaluated using:

### R² Score

Measures how well the model explains the variation in the target values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction error.

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

## 📈 Results

The project includes:

* Data visualization
* Regression line visualization
* Actual vs Predicted score comparison
* R² Score value:0.9243909691068846
* MSE value:17.123345246432496
* RMSE value:4.138036399843831
* MAE value:3.562216092419423

* Prediction for a new student

## 🔮 New Student Prediction

The trained model can predict the expected score of a new student based on their study hours.
example:
hours = [[9.25]]

prediction = model.predict(hours)

print("Predicted Score:", prediction[0])


## 📝 Conclusion

The Linear Regression model was used to predict students' exam scores based on their study hours. The project demonstrates the basic Machine Learning workflow, including data loading, data visualization, train-test splitting, model training, prediction, and model evaluation.

The trained model can also be used to predict the expected score of a new student based on their study hours.

## 📁 Project Structure

```text
Student-Score-Prediction/
│
├── student_scoreprediction.ipynb
├── student.csv
└── README.md
```

## 🚀 Future Improvements

Possible future improvements include:

* Using more student-related features.
* Trying other Machine Learning algorithms.
* Using a larger dataset.
* Improving model performance.
* Deploying the model as a web application.

## 👩‍💻 Author

**Sneha**

This project was created as part of my Machine Learning learning journey.
