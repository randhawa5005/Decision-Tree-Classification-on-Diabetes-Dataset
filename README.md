# Decision-Tree-Classification-on-Diabetes-Dataset
Overview

This project demonstrates how to use a Decision Tree Classifier to predict diabetes in patients using a well-known dataset. The primary goal is to classify patients as diabetic or non-diabetic based on several medical features such as glucose level, blood pressure, BMI, etc.

Dataset

The dataset used in this project is the Pima Indians Diabetes Database. This dataset is part of the UCI Machine Learning Repository and contains information about 768 patients, including the following features:

Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration

Blood Pressure: Diastolic blood pressure (mm Hg)

Skin Thickness: Triceps skinfold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)^2)

Diabetes Pedigree Function: A function that scores the likelihood of diabetes based on family history

Age: Age in years

Outcome: Class variable (0 or 1) where 1 indicates the presence of diabetes

1. Importing Required Libraries Let's first load the required libraries.

2. Loading Data Let's first load the required Diabetes dataset using pandas read CSV function. You can download the data here (datasets_set.csv)

Feature Selection Here, you need to divide given columns into two types of variables dependent(or target variable) and independent variable(or feature variables).

3. Splitting Data To understand model performance, dividing the dataset into a training set and a test set is a good strategy.

4. Let's split the dataset by using function train_test_split(). You need to pass 3 parameters features, target, and test_set size.

5. Building Decision Tree Model Let's create a Decision Tree Model using Scikit-learn.

6. Evaluating Model Let's estimate, how accurately the classifier or model can predict the type of cultivars.

Accuracy can be computed by comparing actual test set values and predicted values.

7.Visualizing Decision Trees

Conclusion

This project successfully demonstrates the application of Decision Tree Classification on a medical dataset. The model provides a reasonable accuracy in predicting diabetes, and the visual representation of the tree helps in understanding the decision-making process.
