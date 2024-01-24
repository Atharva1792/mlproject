## End to End Machine Learning Project

Problem statement:
This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

Dataset information:
gender : sex of students -> (Male/female)
race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
lunch : having lunch before test (standard or free/reduced)
test preparation course : complete or not complete before test
reading score
writing score
math score(target variable)

Feature Engineering:
Standard Scaler for numerical data
One Hot Encoding for categorical data

ML Algorithms used:
Random Forest Regressor
Decision Tree Regressor
Gradient Boosting Regressor
LinearRegression
XGBRegressor
CatBoostRegressor
AdaBoostRegressor
