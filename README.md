

# Finding Donors for Charities 
## Table of Content
  * [Overview](#overview)
  * [Problem Statement](#problem-statement)
  * [Objective](#objective) 
  *  [Motivation](#motivation)
  * [Data Overview](#data-overview) 
  * [Technologies Used](#technologies-used)
  * [Bug ](#bug)
  * [Team](#team)

## Overview
In this project, apply supervised learning techniques and an analytical mind on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause. You will first explore the data to learn how the census data is recorded. Next, you will apply a series of transformations and preprocessing techniques to manipulate the data into a workable format. You will then evaluate several supervised learners of your choice on the data, and consider which is best suited for the solution. Afterwards, you will optimize the model you've selected and present it as your solution to CharityML. Finally, you will explore the chosen model and its predictions under the hood, to see just how well it's performing when considering the data it's given. predicted selling price to your statistics. 

## Problem Statement 
Build an algorithm to best identify potential donors.

## Objective 
• My goal was to evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation yield while also reducing the total number of letters being sent.  
• Implemented a pipeline in Python that will train and predict on the supervised learning algorithm given. I used the Grid Search method to tune the parameters of all algorithms and Gradient Boosting Classifier to extract features importance. 

## Data Overview 
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper  _"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",_  by Ron Kohavi. You may find this paper  [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on  [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Features**

-   `age`: Age
-   `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
-   `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
-   `education-num`: Number of educational years completed
-   `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
-   `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
-   `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
-   `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
-   `sex`: Sex (Female, Male)
-   `capital-gain`: Monetary Capital Gains
-   `capital-loss`: Monetary Capital Losses
-   `hours-per-week`: Average Hours Per Week Worked
-   `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**

-   `income`: Income Class (<=50K, >50K)

## Technologies Used 
![](https://forthebadge.com/images/badges/made-with-python.svg)<br/>
[<img target="_blank" src="https://github.com/scikit-learn/scikit-learn/blob/master/doc/logos/scikit-learn-logo-small.png">](https://github.com/scikit-learn/)
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/numpy.png" width=170>
<img target="_blank" src="https://github.com/ditikrushna/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/blob/master/Resource/pandas.jpeg" width=170>

## Bug 
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/ditikrushna/FINDING-DONORS-FOR-CHARITIES/issues/new) by including your search query and the expected result.



## Team  
[![Ditikrushna Giri](https://ditikrushna.me/images/diti.jpg)](https://ditikrushna.me/) |
-|
[Ditikrushan Giri](https://ditikrushna.me/) |)
