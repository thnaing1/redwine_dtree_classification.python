# Decision Tree Classification of Portuguese Vinho Verde Red Wines


This is a decision tree classifier to correctly classify whether a wine is above average or below average.

Title: Classification of Wine Quality using the Decision Tree Classifier 

Data Collection method: UC, Irvine Machine Learning Repository

Sources: https://archive.ics.uci.edu/ml/datasets/wine+Quality

Coding Language: Python

The Dataset

This dataset is of various red wines of the Portuguese "Vinho Verde" variety. These wines are described by 11 characteristic features: 
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol

and one output variable:
12 - quality(score between 0 and 10)

Task

The goal is to use the 11 characteristic features - which describe the physicochemical properties of the red wine- to classify the wine quality score. I will first break the output variable into 2 classes: 1 and 0. 1 represents all the wines that scored from 7 to 10(above average), and 0 represents all the wines that scored from 0 to 6(below average). The classfier will then try to predict which class each wine belongs to using the feature variables. The machine learning algorithm I will use to do this is the Decision Tree Classifier.

Notes
- The dt_algo file shows the decision tree coded from scratch as well as the decision tree created using the Sci-Kit learn library. It contains annotations to demonstrate my thought process and explain the code in detail. 
- Alternatively, the red_wine decision tree classification file only contains the simplified version the decision tree created using the Sci-Kit learn library
