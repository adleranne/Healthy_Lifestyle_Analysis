# Healthy_Lifestyle_Analysis
Final Data Analytics Bootcamp Project

Lifestyle is a diverse concept but usually referred to the way someone lives their live, which can be in a material/socio-economic context (e.g. expensive lifestyle, consumption habbits), socio-cultural related (e.g. urban lifestyle, certain believes/values/interests) or even health related (e.g. unhealthy lifestyle, work-life-balance). The research of lifestyle focussing on health and well being is part of the interdiscplinary field of "lifestyle medicine", which is "a branch of medicine focused on preventive healthcare and self-care dealing with research, prevention, and treatment of disorders caused by lifestyle factors". (https://en.wikipedia.org/wiki/Lifestyle_medicine).

This project takes the 'Lifestyle and Well Being' dataset from kaggle which is based on an online questionnaire from the www.Authentic-Happiness.com project, containing about 16.000 responses collected between 2015 and 2021 from all over the world. The goal of this project is to check which lifestyle features are contributing to a healthy bmi (target/KPI for this project), which is one of the main influencing factors on lifestyle related deseases (like diabetes, heart desease etc.).

The Dashboard, based on the results shows the status quo and development of the healthy bmi over time. It also displays the features for each lifestyle dimension (derived from a PCA, using all single features) and highlights the top5 features to discriminate between healthy and non-healthy bmi (derived from the classification analysis). The Dashboard can be filtered by age and gender and always shows the values for a selected year. The PCA and Classification analysis are based on all available data (2015 to 2021).

Steps of analysis:
1. Data cleaning
2. EDA - focussing on Factor Analysis/PCA to reduce the 18 features of the questionnaire to lifestyle dimensions
3. Classification Analysis - checking, which features are most important for classifying a healthy bmi
4. Creating a PowerBI Dashboard of the results

Limitations & possible Improvements:
1. The underlying questionnaire was originally developed for a different purpose (to calculate a work-life-balance score for each respondent). Thus the questions and scales of the questions are not optimized for this project. To improve the quality of the analysis, a new questionnaire would need to be developed, tailored to the specific cause of this project.
2. The BMI measurement is only given as a binary value (below or above 25). By collecting precise information about the actual bmi value, a regression analysis could be used instead of a classification to determine the most influencial lifestyle aspects. That would make it much easier to interpret the importance of different features.
3. Only very vew demographic information is available for the data - by, for instance, including the country or running a project for just a single country, the resulting dashboard of such a project could help the public health sector to derive strategies and communication campaigns in order to successfully change people behaviour towards a more healthy lifestyle.
4. The capabilities of PowerBI and the reporting of such a study can be further exploited. The Dashboard could be the starting point of analysis and drill down functions could be used, to further analyse need for actions and single features of interest. 

Links:
1. Original questionnaire: http://www.authentic-happiness.com/your-life-satisfaction-score
2. Data source: https://www.kaggle.com/datasets/ydalat/lifestyle-and-wellbeing-data

