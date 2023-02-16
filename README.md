# Innovative-Stroke-Care-The-Power-of-Data-Machine-Learning
- Complete Project of Data Analysis and Machine Learning on"Innovative Stroke Care" using Python Programming And Machine Learning.
- For Visuals we use the Python libraries like Matplotlib, Seaborn & plotly.express in Anaconda(Jupyter Notebook).

## Introduction
- Nowadays, stroke is a major health-related challenge. 
- Stroke, also known as cerebrovascular accident, consists of a neurological disease that can result from ischemia or hemorrhage of the brain arteries, and usually       leads to heterogeneous motor and cognitive impairments that compromise functionality. 
- Annually, stroke affects about 16 million individuals worldwide and is associated with enormous societal costs. 
- WHO identifies ischaemic heart disease and stroke as the two leading causes of mortality and disability worldwide.
- According to the American Heart Association, stroke is considered a severe health issue due to its high mortality rate.

## Context
- The data was obtained from Kaggle :[https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset]

## Dataset
- This dataset consist of Records:5109 and Features:11

## Python Libraries used in Project
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- import plotly.express as px
- from plotly.subplots import make_subplots
- import warnings
  warnings.filterwarnings('ignore')
  
## Data Preparation/Cleaning
- As the dataset from kaggle was not very suitable for data analysis, we had to change the format of some data in the dataset. We also had to do separate data           preparation for exploratory analysis and machine learning.
- Some of our data preparation were:
- Treating NaN values with mean.
- Cleaning the textual data into a form that would be suitable for Python's Jupyter Notebook.
- Encoding the categorical variables so that it can be fit into the classifer models later.
- Separating the data into Predicted and Target variables.
- Separating the data into training and testing sets (Training Sets: Testing Sets = 75% : 25%).

## Use of Classifier in the Machine Learning Models.
- Classification gives out discrete values.
- Given a group of data, this method helps group the data into different groups.
- In classification, the nature of the predicted data is unordered.
- In classification, the nature of the predicted data is unordered.
- Classification is done by measuring the accuracy.

## ML Model Used in project:
- DecisionTree Classifier = 94.05%
- RandomForest Classifier = 93.97%
- KNeighborsClassifier    = 94.20%
- GaussianNB              = 86.01
- SVC                     = 94.13
- AdaBoostClassifier      = 93.97

## Conclusion
- KNN algorithm yields the highest accuracy, 94.2%. Any accuracy above 80% is considered good, but be careful because if your accuracy is extremely high, it may be too   good to be true (an example of Overfitting). Thus, 94.2% is the ideal accuracy! 
- Out of the 10 features we examined, the top 3 significant features that helped us classify between a positive & negative maximum stroke achieved by Avg_glucose        _level,  Age and  Bmi .
- Our machine learning algorithm can now classify patients with Brain Stroke. Now we can properly thrombectomy, & get them the help they needs to recover. By detecting   these features early, we may prevent worse symptoms from arising later. 

