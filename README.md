# Heart Disease Prediction using Machine Learning.

This project applies various Machine Learning and Data Science python-based tools like *pandas, numpy, matplotlib, scikit-learn etc.*, to predict whether a patient has heart disease or not, given medical attributes.

Note: This project has been completely done on a Colab notebook, hence no environment setup in the github repo.
https://colab.research.google.com/drive/1lRqch_liVMrd6pLUx-3gj2Rpis7UX4N6?usp=sharing

Notify me if you want to get added.

## Approaches:
1) Problem Definition
2) Data
3) Evaluation
4) Features
5) Modelling
6) Experimentation

## 1. Problem Definition

Given the clinincal parameters such as age, sex, blood sugar level etc., is it possible to predict whether or not the patient has heart disease?

## 2. Data

Original data has been sourced from the Cleveland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Heart+Disease
In this example, 14 medical attributes have been used.

## 3. Evaluation

If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

## 4. Features

Create a data dictionary

* age- age in years
* sex - (1 = male, 0 = female)
* cp - chest pain type
* trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern.
* chol - serum cholestoral in mg/dl
* fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg - resting electrocardiographic results
* thalach - maximum heart rate achieved
* exang - exercise induced angina (1 = yes; 0 = no)
* oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
* slope - the slope of the peak exercise ST segment
* ca - number of major vessels (0-3) colored by flourosopy
* thal - thalium stress result
* target - have disease or not (1 = yes, 0 = no)

Note: Visit https://archive.ics.uci.edu/ml/datasets/Heart+Disease if you seek elaboration on parameters.

The results can be found in the Results folder of this repository.

## 5. Data Analysis and Modelling

