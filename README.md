# ASA Datafest
Increasing effectivity of ABA Pro Bono Services

##  Problem Statement & Purpose
American Bar Association is facing problem with the declining usage of Pro Bono Services throughout United States especially in the smaller cities/states, to solve that they started collecting data about clients, attorneys, questions posted and the places from where questions are asked from. Now based on all that data which is collected over the span of 10 years ABA is looking for some young data analyst to use Machine Learning tools and Statistics to provide a solution which would improve the effectivity of American Bar Association in providing Pro Bono Services to much more needy citizens.

## Analysis
To manage and pre-process this large dataset provided by ABA, I collaborated with <a href = "https://github.com/barri7n">@barri7n</a> where we cleaned the unwanted texts from question posts, imputed NA values in columns, merged clients and attorney to understand the ratio as well as used the states they're located in using geo_location dataframe. 

After some thorough pre-processing, we used multiple visualisations techniques to analyse the relation between multiple features. Found some intresting patterns in the time-zone, data and trend of questions posted and the number of questions asked by each US State as well as the ratio of attorney to client by US States over the year.

Based on these patterns provided the plan-of-action which would improve the effectivity of Pro Bono Services in America. Used Time Series to advice ABA to increase workforce in US state with lowest attorney to client ratio which were Texas and Florida over the span of 10 years alongside the increase in trend of questions asked in those states. Used NLP model BertTopic on various cleaned question posts provided by ABA. Model returned 8 major clusters of questions asked by clients in USA classifying the text into major categories using similarity matrix. ABA can use these categories to cut down the workforce in other categories and maximize attorneys who're specialised in these categories.

## Technology Used
Python, Google Collab 
