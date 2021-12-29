---
date: 2021-12-16T10:58:08-04:00
featured_image: "/images/Projects/project1.png"
tags: []
title: "Project 1: Hotel Bookings Cancellation Classification"
description: "A prediction model classify a hotel booking׳s likelihood to be canceled"
---
# Abstract
In tourism and travel-related industries, most of the research on Revenue Management demand forecasting and prediction problems employ data from the aviation industry, in the format known as the Passenger Name Record (PNR). This is a format developed by the aviation industry. 
The main goal is to generate meaningful estimators from the data set we have and then choose the model that best predicts cancellation by comparing it to the accuracy ratings of several ML models. Following the data science life cycle, I will work towards this aim through several processes. I present a study approach that utilizes a variety of methods and algorithms including (Logistic Regression, Random Forest, K-Folds cross-validation, Decision Tree, and XgBoost) to make a prediction model classify a hotel booking׳s likelihood to be canceled. 
The results show that there is one feature (called reservation status) that has a very high correlation with the target column (is canceled), and a logistic regression classifier gives an accuracy of 99% while the same model gives an accuracy of 81% when this feature is removed. As a result, I choose to delete the feature and conduct a fair comparison of the different classifiers. The XgBoost classifier achieved the highest accuracy of 88%.

***Keywords***: Hotel cancellation prediction, Classification, logistic regression, Random Forest, K-Fold CV, Grid search, XgBoost

# Tools.
{{< figure src="/images/Projects/Project1 tools.png" title="" >}}

*	Python 3.
* 	Pandas Library.
*	NumPy Library.
*	Plolty Library.
*	Sklearn Library.
*	Keras APIs.
* 	Local Jupter Notebook.
* 	Word and power point.

# Prject Stages 
{{< figure src="/images/Projects/Project1 Stages.png" title="" >}}

# Data Modeling Stages
{{< figure src="/images/Projects/Data Modeling Pipline.png" title="">}}

# Conclusion
{{< figure src="/images/Projects/project1.png" title="">}}

# More Resouces

* For more details see the project [repository](https://github.com/heba14101998/Hotel-Bookings-Cancellation.git) on github.

* Dispaly the project detailed report from [here](https://github.com/heba14101998/Hotel-Bookings-Cancellation/blob/main/Hotel%20booking%20cancellation%20Report.pdf)

* Dispaly the project presentation from [here](https://github.com/heba14101998/Hotel-Bookings-Cancellation/blob/main/Hotel%20booking%20cancellation%20presentation.pdf)

* Dispaly the project notebook from [here](https://github.com/heba14101998/Hotel-Bookings-Cancellation/blob/main/Hotel%20Bookings%20code.html)


