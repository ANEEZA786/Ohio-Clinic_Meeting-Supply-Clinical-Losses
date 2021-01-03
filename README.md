# Overview
In this project, solved the Classification Problem because labels is in categorical form in which Ohio Clinic was facing losses for third consecutive year. 
However, hospital was incurring losses despite having the finest doctors & other clinical staff & no lack pf scheduled appointments.
For this purpose, first cross check wheather the features within the dataset were relevant to the problem or not.
From the data dump, concluded that to do following with given information:
1- What's the reason that losses are coming up even though with the rate of appointments going up?
2- What's the reason behind that patient's are not reporting at the time of their scheduled appointment. For this purpose, come up with the solution that remind patients about their apppointments.
Likewise come up with a method to determine weather a patient would show up on the basis of their characteristics.

# Details
I have looked into the dataset and managed a few problems like unifying names, removing ambigious data such as Handicap, perform some feature engineering converting categorical data 
into numerical data e.g. converting 'Gender', 'Status' and 'DaysOfTheWeek' into Numerical Data. I have also investigated most of independent variables in the dataset and made a 
few observations comparing them to each other as well as to the dependent one (Status). As this was only an exploratory analysis, many potential correlations find the correlation
of dependent variable to independent variables. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and corelations.

# Findings

The most important findings are:

1- Scheduling visits started on 2014-1-15 and ended on 2015-6-08.
2- The distribution of appointments among days of week (Monday-Friday) is almost equal witha little bit less visits on Thursday and Friday. There are 24 visits on Saturday and none on Sunday.
3- 10 days on average patients awaited for an appointment. 50% of patients waited up to 4 days and 75% up to 15 days for an appointment. The longest awaitibng time was 179 days.
There are handicap categories with most of the people not being handicapted. That's data is bit ambigious, so prefer to removed it from the dataset to avoid complexity.
4- There are many vaery young people in the dataset (most of them of age 0) that is error in the dataset cz that patient's are infants. So, prefer to remove that from the data.
if these values have no or minor impact on the dataset. as we measure there are only 6 values in the given dataset so we drop these values.
5- As observed that, values within AwaitingTime appeared to be negative, and hence it made sense to transform them into positive values. 

# Statistical Analysis Scope

 - Data Wrangling
 - Exploratory Data Aanalysis (EDA)
 - Examination of central tendency and spread
 - Data Visulization
