# Water-quality-analysis using- machine learning classification algorithms

## Introduction:
 The Water Quality Analysis System using Machine Learning is a computerbased program that utilizes machine learning algorithms to predict and monitor the quality of water in each area. The system takes in data from various sources such as water samples, weather conditions, and land-use patterns, and applies statistical and machine learning models to identify patterns and predict potential contaminants. This system provides a comprehensive and efficient approach to water quality monitoring that can significantly improve water management and public health. This paper discusses the development, implementation, and validation of this system and highlights its potential benefits in ensuring safe and sustainable water resources. The aim is to investigate machine learning-based techniques for water quality forecasting by predicting results with the best accuracy machine learning algorithms. During the last few decades, the quality of water has deteriorated significantly due to pollution and many other issues. As a consequence of this, there is a need for a model that can make accurateprojections about water quality. The comparative analysis of different machine learning approaches like Logistic regression, Knearest neighbor, Decision Tree (DT), Random Forest used for the water quality classification with hidhest accuracy of 65.32%. Our model was able to detect changes in the water quality over 
time, and even estimate the overall health of the water quality in different areas.

## Data Preprocessing:
 The First step of pre-processing is to find whether missing values are present. Since no null values are present in our dataset no need to do any imputation. Visualization of data is an imperative aspect of data science. It helps to understand data and also to explain the data to another person. Python has several interesting visualization libraries such as Matplotlib, Seaborn etc.Then come the encoding part to convert the categorical features we did label encoding using label encoder. Label Encoder is the part of SciKit Learn libraryin Python and used to convert categorical data, or text data, into numbers, which our predictive models can better understand.

 ## Splitting the data:
  Test train split is a popular method for splitting a dataset into training and testing subsets. It is a simple and effective way to evaluate the performance of a machine learning model on an unseen dataset. Splitting a dataset is a common task when preprocessing data for machinelearning algorithms or other statistical analysis. The process involves randomly allocating a given dataset into two or more subsets,often referred to as training and testing sets. The purpose of splitting a dataset is to give the machine learning algorithm a definitive set of data to train on and then measure its accuracy on the testing set.Splitting the data and setting the test size as 1/3. Rest 2/3 is used for training the data.
  

 ## Model Building: 
  Classification models are used to predict the class or category of a target variable based on a set of predictor variables. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into several classes or groups. The Classification algorithm uses labelled input data because it is a supervised learning technique and comprises input and output information. A discrete output function (y) is transferred to an input variable in 
the classification process (x).

## Result Analysis:
 ![image](https://github.com/ThankaKumar/Water-quality-analysis/assets/114381635/88f23b71-9723-4969-9259-0b6b5981090c)
  
   This shows the accuracy obtained by each models. To get maximum analysis we used four machine learning algorithms like Logistic Regression,Random Forest, Decision Tree and K-Nearest Neighbor. The accuracy obtained by each model are Logistic Regression as 62.846%, Random Forest as 62.846%, K-Nearest Neighbor as 65.342% and Decision Tree as 64.510%

## Conclusion:
 In conclusion, machine learning classification algorithms can be an effective tool for water quality analysis. By training models on large datasets of
water quality parameters and their corresponding classification labels (portableor non-portable), these algorithms can accurately predict the water quality class
of new samples based on their input parameters. Machine learning algorithms like K-nearest Neighbor, Random Forest, Decision Tree, and Logistic Regression are used to predict the output. By training these algorithms on a set of labeled data, they can accurately classify and predict the quality of water samples based on various parameters such as pH, temperature, dissolvedoxygen, turbidity, etc. Then accuracy of each models are calculated by f1 score. K-Nearest Neighbor algorithm gives highest accuracy of 65%. Therefore, while machine learning can be a valuable tool for water quality analysis, it should be used in conjunction with other methods such as traditional laboratory analysis and expert interpretation.



