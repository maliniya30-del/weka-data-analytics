# weka-data-analytics

1.🌍 Weather Pollution Data Analytics using WEKA

This project focuses on analyzing weather and air pollution data using the WEKA data mining tool to identify patterns, trends, and relationships between environmental factors.

2.📌 Project Overview

The objective of this project is to explore how different weather parameters (such as temperature, humidity, and wind speed) influence air pollution levels. By applying data preprocessing and machine learning techniques in WEKA, meaningful insights were extracted from the dataset.

3.🛠️ Tools & Technologies

WEKA (Waikato Environment for Knowledge Analysis)
Data Preprocessing Techniques
Classification & Clustering Algorithms
Data Visualization (WEKA Explorer)

4.🔍 Key Features

Cleaned and preprocessed raw weather and pollution datasets
Applied classification algorithms (e.g., J48, Naive Bayes) to predict pollution levels
Analyzed correlations between weather conditions and pollution indicators
Evaluated model performance using accuracy and error metrics

5.📊 Outcomes

Research Question 1

1. What are the significant factors influencing weather to play outdoor activities?
The analysis of the weather–pollution dataset identified several environmental factors that influence the decision to participate in outdoor activities. These factors include weather conditions and air pollution indicators such as outlook, temperature, humidity, wind conditions, traffic level, industrial emissions, PM25, and PM10.
Among these attributes, PM25 (fine particulate matter) was identified as the most significant factor affecting outdoor activity decisions. The decision tree model selected PM25 as the root node, indicating that it has the highest predictive importance in determining whether outdoor activities should take place.
The results show that when PM25 levels are low (≤ 80), outdoor activities are more likely to occur, whereas higher PM25 levels (> 80) significantly reduce the likelihood of safe outdoor participation due to increased air pollution and potential health risks.
Other supporting factors such as temperature, humidity, traffic level, and industrial emissions also influence the decision, but their impact is comparatively lower than that of pollution indicators.
Therefore, the study concludes that air pollution levels, particularly PM25, are the most significant factors influencing outdoor activity decisions, followed by general weather conditions.
________________________________________

Research Question 2

2. Can a predictive model be developed to accurately identify the risk of playing outdoor games?
Yes, a predictive model can be successfully developed to identify the risk of playing outdoor games based on weather and pollution data. In this study, a J48 decision tree classifier was implemented using WEKA to analyse the dataset and generate prediction rules.
The model was evaluated using 10-fold cross-validation, which ensures reliable and unbiased performance evaluation. The results show that the model achieved a classification accuracy of 93.33%, correctly predicting 28 out of 30 instances. The Kappa statistic value of 0.861 further indicates strong agreement between the predicted and actual outcomes, demonstrating the reliability of the model.
The generated decision rule indicates that PM25 pollution level is the primary determinant in identifying the safety of outdoor activities. When pollution levels exceed the threshold value, the model predicts that outdoor activities should be avoided due to potential health risks.
Thus, the results confirm that machine learning techniques can effectively develop predictive models to assess the risk associated with outdoor activities under different environmental conditions.

6.🚀 Learning Outcomes
Hands-on experience with data mining using WEKA
Understanding of machine learning algorithms and evaluation techniques
Improved data preprocessing and analytical skills

output screenshots are as below:

https://github.com/maliniya30-del/weka-data-analytics/blob/main/Overall%20analysis.png

https://github.com/maliniya30-del/weka-data-analytics/blob/main/Feature%20selection.png



