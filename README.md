## Pima Diabetes Analysis

![diabets_](https://github.com/hayasalman/Pima-Diabetes-Analysis/assets/71796909/55aad137-2468-4e23-96f5-54de056a3c1c)

## Overview

Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe. In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima tribe.

### Objective

To analyze the different aspects of diabetes by doing Exploratory Data Analysis (EDA).

### Dataset Feature Description

The dataset has the following information:

- **Pregnancies**: Number of times pregnant.
- **Glucose**: Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skin fold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: A function that scores the likelihood of diabetes based on family history.
- **Age**: Age in years.
- **Outcome**: Class variable (0: a person is not diabetic or 1: a person is diabetic).

## About The Dataset

- In total, this dataset has 768 observations and 9 features.
- Data source stored as CSV file and can be accessed through this link : [Dataset](https://github.com/hayasalman/Pima-Diabetes-Analysis/blob/main/diabetes.csv)

## Coding

-  Python Integrated Development Environment (IDE) : Jupyter Notebooks.

   **Packeges used**
   
  * **pandas - numby** : used for data manipulation.
  * **matplotlib - seaborn** : used for data visualtion.

## Approches & Methodologies

- Performed a quick overview about the dataset like the dataset shape , data types, detected any missing or duplicated values.

- Performed exploratory data analysis (EDA) :

    1. **Univariate Analysis**
       
       - **Univariate Non-graphical Analysis** : by using describe() method to return a summary of descriptive statistics about the numeric 
           features in this dataset.
      
       - **Univariate Graphical Analysis** : by using visualizations for only one dimension of the dataset (numeric/categorical variables) like : 
           histograms and distribution plot to identify the data distribution, or box and whisker plot to analyze the interquartile range and 
           detect the outliers in this dataset.
         
    2. **Bivariate Analysis**
      
       - **Bivariate Graphical Analysis** : by using conditional filtering that combines two different variables in order to find out a specific 
           insight about the dataset, or the correlation matrix that determines the associations between different variables.

       - **Bivariate Graphical Analysis** :  by using visualizations for two dimension of the dataset (the numeric/categorical variables) like : 
           scatter plot to identify the kind of the relationship between two different numeric variables (positive/negative relationships), pair 
           plot that will return a different scatter and distribution plots of all the numeric variables based on categorical variable , or heatmap 
           plot to show the different associations between the different variables.


 ## Data-driven Insights

  *In this dataset we found that:*
  
 - Most of the women in this dataset have a blood pressure between **60 - 80 mm Hg**.
   
 - A person who has the highest glucose has **43 BMI**.
   
 - There are 343 women who have glucose levels above the mean of glucose levels **(glucose AVG : 121.67)**.
   
 - There are 22 women who have blood pressure equal to the median of blood pressure **(blood pressure median : 72)** and BMI is less than the 
    median of BMI **(BMI median : 32)**.
  
- Most of the women are not diabetic, while the other women are diabetic.
  
- Women who are not diabetic most of them have glucose levels that don't exceed **150** , while in the case of women who are diabetic have glucose 
  levels up to **200**.

- Most women approximately score between **0-0.8** for diabetes likelihood function regardless if they are diabetics or not and a few of them score 
  above **1.5**.

## References

[Pima Diabets Analysis Project File](https://github.com/hayasalman/Pima-Diabetes-Analysis/blob/main/Pima%20Diabetes%20Analysis_.ipynb)

## Sugesstions

- In fact, the pima dataset is a good use case to build a machine learning classification model that predicts if the person is a diabetic or not.

  
