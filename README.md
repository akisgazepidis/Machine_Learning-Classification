# Machine_Learning-Classification

I have to make clear that this project is for training reasons and to help me understand better how to treat a classification problem. There may exist mistakes, thus if you notice anything let me know.

## Main Goal
Use the dataset which contains many characteristics of people in order to train some models to classify people if they have a high or low chance of a heart disease based on their characteristics. After that to choose the best for use. 

## Information about Dataset
In this project i used a dataset from Kaggle.com that concerns people from Cleveland.

The dataset i chose was cleaned.The cleaned data set contains information of 14 attributes:
1) age
2) sex: 0 = female, 1 = male
3) cp = chest pain type (4 values)
4) trestbps = resting blood pressure
5) chol =  serum cholestoral in mg/dl
6) fbs = fasting blood sugar > 120 mg/dl
7) testecg =  resting electrocardiographic results (values 0,1,2)
8) thalach =  maximum heart rate achieved
9) exang =  exercise induced angina
10) oldpeak = ST depression induced by exercise relative to rest
11) slope = the slope of the peak exercise ST segment
12) ca =  number of major vessels (0-3) colored by flourosopy
13) thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
14) target: 0= less chance of heart attack 1= more chance of heart attack

There were no missing values.

## Model's metrics
After trial and error the model i chose was XgBoostRegressor. It reached a F1 score: 0.903 with Precision score: 0.933 . Because i have to deal with a problem to classify if a person is possible to have a heart attack or not Precision was the main factor for me to in order to choose the suitable model.  
