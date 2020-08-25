---
author: Yashparna De
date: "2020-08-24T13:36:06+06:00"
feature_image: images/blog/cr1.jpg
image: images/blog/cr.jpg
title: 'Supervised machine learning algorithms'
---
### -Differences and similarities, Where to use what?


We know that there are numerous algorithms that can be used for modeling in data science. But with just data given with no specifications, its difficult to understand which one to use where. In this blog post I’m going to focus on supervised learning, i.e.  Regression and classification. The similarities, differences and their use.

Classification and Regression are two major prediction problems which are usually dealt in Data mining. Predictive modelling is the technique of developing a model or function using the historic data to predict the new data.



**Definitions:**

**Classification** is the process of finding or discovering a model or function which helps in separating the data into multiple categorical classes i.e. discrete values. In classification, data is categorized under different labels according to some parameters given in input and then the labels are predicted for the data.
The derived mapping function could be demonstrated in the form of “IF-THEN” rules. The classification process deal with the problems where the data can be divided into binary or multiple discrete labels.

 Example: Winning any simple sports by team A can be classified as YES or NO.

**Regression** is the process of finding a model or function for distinguishing the data into continuous real values instead of using classes or discrete values. It can also identify the distribution movement depending on the historical data. Because a regression predictive model predicts a quantity, therefore, the skill of the model must be reported as an error in those predictions

Example: Rainfall in a particular area.

>Differences and similarities?


![difference example](images/blog/cr2.png)


Regression and classification are categorized under the same umbrella of supervised machine learning. Both share the same concept of utilizing known datasets (referred to as training datasets) to make predictions.

In supervised learning, an algorithm is employed to learn the mapping function from the input variable (x) to the output variable (y); that is y = f(X).
The objective of such a problem is to approximate the mapping function (f) as accurately as possible such that whenever there is a new input data (x), the output variable (y) for the dataset can be predicted.

But this is where the similarity ends.

**The main difference between them is that the output variable in regression is numerical (or continuous) while that for classification is categorical (or discrete).**

As defined by Dr. Michael J. Garbade in his blog:

In machine learning, **regression algorithms** attempt to estimate the mapping function (f) from the input variables (x) to numerical or continuous output variables (y).
In this case, y is a real value, which can be an integer or a floating point value. Therefore, regression prediction problems are usually quantities or sizes.

For example, when provided with a dataset about houses, and you are asked to predict their prices, that is a regression task because price will be a continuous output.


On the other hand, classification algorithms attempt to estimate the mapping function (f) from the input variables (x) to discrete or categorical output variables (y).
In this case, y is a category that the mapping function predicts. If provided with a single or several input variables, a classification model will attempt to predict the value of a single or several conclusions.

For example, when provided with a dataset about houses, a classification algorithm can try to predict whether the prices for the houses “sell more or less than the recommended retail price.”
Here, the houses will be classified whether their prices fall into two discrete categories: above or below the said price.

![differences](images/blog/cr3.jpg)


Seeing and understanding the above differences, is the basic step towards understanding and knowing what method to use where and will help us in applying the respective to our data set. 


To conclude, Classification technique provides the predictive model or function which predicts the new data in discrete categories or labels with the help of the historic data. Conversely, the regression method models continuous-valued functions which means it predicts the data in continuous numeric data.
Selecting the correct algorithm for your machine learning problem is critical for the realization of the results you need.

Hence, its important to understand the basic concept of which to use where.



For more understanding and to work with the above stated models, click on the below links to go through some R codes and detailed explanation with examples.

•	https://www.kaggle.com/meepbobeep/intro-to-regression-and-classification-in-r

•	https://machinelearningmastery.com/classification-versus-regression-in-machine-learning/#:~:text=A%20classification%20algorithm%20may%20predict,form%20of%20an%20integer%20quantity.

