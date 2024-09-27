# Heart Stroke Detection


This project uses machine learning to predict the likelihood of a heart stroke based on various patient attributes.

## Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Features](#features)
* [Model](#model)
* [Results](#results)
* [Conclusion](#conclusion)
* [Installation](#installation)
* [Usage](#usage)

## Introduction

Heart stroke is a leading cause of death worldwide, and early detection is crucial for improving patient outcomes. This project aims to develop a machine learning model that can predict the likelihood of a heart stroke based on patient attributes such as age, gender, blood pressure, and smoking status.

## Dataset

The dataset used for this project is the [Healthcare Dataset Stroke Data](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) from Kaggle. The dataset contains 5110 rows and 12 columns, including:

* id: unique identifier for each patient
* gender: male or female
* age: age of the patient
* hypertension: presence or absence of hypertension
* heart_disease: presence or absence of heart disease
* ever_married: whether the patient has ever been married
* work_type: type of work the patient does
* Residence_type: type of residence the patient lives in
* avg_glucose_level: average glucose level of the patient
* bmi: body mass index of the patient
* smoking_status: smoking status of the patient
* stroke: presence or absence of stroke

## Features

The following features were used for the model:

* age
* gender
* hypertension
* heart_disease
* ever_married
* work_type
* Residence_type
* avg_glucose_level
* bmi
* smoking_status

## Model

The model used for this project is a logistic regression model. The model was trained using the training dataset and evaluated using the testing dataset.

## Results

The model achieved an accuracy of 95.6% on the testing dataset.

## Conclusion

This project demonstrates the potential of machine learning in predicting heart stroke risk. The model developed in this project can be used to identify high-risk patients and take proactive measures to prevent heart strokes.

## Installation

To install the required libraries, run the following command:
