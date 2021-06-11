# Internship_GRIP_2021
Data Science and Business Analytics Internship at Sparks Foundation

# Problem Statement
Predict the percentage of an student based on the no. of study hours

# Feature Description

Hours: Number of hours student has studied in a day.(Independent Variable)
Scores: Percentage of marks obtained by the student corresponding to the number of study hours.(Target Variable)

# Work flow

1. Understanding the data
2. Building a model
3. Evaluationg the model
4. Predicting the score if a student studies for 9.25 hrs/ day?

# Summary of the EDA(Understanding data)

1. The dataset has records of 25 students and their scores correspondong to their number of study hours.
2. The target variable is a number and continous in nature. The first assumption of the Linear regression is satified.
3. There is no mistake in the datatype of the variables when compared to the probelm statement.
4. The student who has studied for the highest number of hours(9.2hrs) is not the topper(88 score).
5. The student who has studied for the least number of hours(1.1hrs) is the one with the lowest score(17).
6. The student with the highest marks of 95 has put in 8.9 hours of study time which is 0.3 hours less than the student who has put in the highest number of study hours(9.2 hours).
7. There are no missing values of any kind(standard/non-standard) or duplicate records in the given dataset.
8. Both the variables are normally distributed and their skew values are closer to 0.
9. There are no outliers in any of the variables.
10. From the lmplot and heatmap,there is a linear relationship between the target and the independent variable.

# Results

Evaluation Metrics:

![image](https://user-images.githubusercontent.com/70081663/121667763-3f590280-cac8-11eb-9d75-a39dcc8960d5.png)

Residual plot:

![image](https://user-images.githubusercontent.com/70081663/121667824-4c75f180-cac8-11eb-97fc-34746f11ba19.png)

Final prediction:

![image](https://user-images.githubusercontent.com/70081663/121668009-7af3cc80-cac8-11eb-8b2e-6d3cf6d89dcf.png)



