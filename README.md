## Title
### **HeartWise Living: A Holistic Wellness Predictor**
![image](https://github.com/keerthyp1999/HeartWise-Living-A-Holistic-Wellness-Predictor-/assets/143935705/c0158e10-b38b-46c5-92df-b08cfc6abedd)

## Problem Statement
In the United States, someone has a heart attack every 40 seconds. Every year, about 805,000 people in the United States have a heart attack. Of these, 605,000 are a first heart attack. The biggest hurdle with heart disease is detecting it. Although there is equipment that can detect heart disease, they are either highly priced or ineffective at calculating the likelihood of heart disease in humans. The mortality rate and overall consequences can be reduced by early identification of cardiac diseases. In the data era, with access to all kinds of data, we can use a variety of machine learning methods to search for hidden patterns. In medical data, the hidden patterns might be used for health diagnosis. Several factors like a person’s vitals like blood pressure, heart rate, cholesterol and blood sugar, food habits and lifestyle, can be used to detect diseases like heart attack in early stages so that it reduces the risk and helps the person to improve lifestyle and live healthy. To address the above stated problem, many categorical models are used to interpret and
predict with highest accuracy the effect of person's vitals and lifestyle on cardiac health.
## Dataset
Data is gathered from UIC's Machine Learning Repository with 76 attributes pertaining to
health and lifestyle of many patients across the globe.
Out of which we carefully chose a subset of 16 features and 3 additional features were
created smoke habits, physical activity , diet using K means clustering method with number of clusters two to find whether these
factors actually affect the heart disease or not.
[https://archive.ics.uci.edu/dataset/45/heart+disease]
## Analysis Methodology
1. Data Cleaning and Pre processing - Performed several data sanitation methods to
address the data issues:

    Null Values Imputation

    Outlier Detection/Imputation

    Class imbalance check

    Normalization

    Correlation and Feature Selection

3. Exploratory Data Analysis - Data analysis was performed to understand the
dependency in theory of features with each other, and each of the features with
cardiac disease.
4. Model Building - Build 6 classification models to find the one that best suits our data
and the one which can predict cardiac arrest for a new set of data with highest
accuracy

    Logistic Regression

    Decision tree

    Random forest

    K nearest Neighbor

    Gaussian Naive Bayes

    Support vector Classifier

6. Prediction - The dataset was divided for training and test with 80% of data for
training. The test dataset was used to test the accuracy of the prediction by each of the
models trained.
7. Results Comparison - Train accuracy, Test accuracy, Precision, Recall, F1-Score,
Sensitivity and Specificity of each of the models were calculated and compared to
find the best model with accurate results

## Conclusion
From the results, we can observe that Random Forest has better train and test accuracy as
well as better specificity and sensitivity when compared to other models. The model is more
sensitive than specific i.e., the model may predict person with no heart disease as heart
disease which is way better than predicting person who has heart disease as no heart disease.
The most contributing features are chest pain and maximum heart rate achieved.
![image](https://github.com/keerthyp1999/HeartWise-Living-A-Holistic-Wellness-Predictor-/assets/143935705/f74d18fd-dd48-4697-a072-196c38d3bace)
![image](https://github.com/keerthyp1999/HeartWise-Living-A-Holistic-Wellness-Predictor-/assets/143935705/1221652d-b4df-4f61-aca1-57a6ef38eab0)








