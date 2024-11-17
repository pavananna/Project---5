# Project---5

Import Dataset:
        For importing the dataset First we have to import the pandas and then we have to use code: pd.read_csv("file path")

Cleaning the dataset: 
              For cleaning the dataset we have find any null value are there are not for that we have use: d1.isnull().sum() then remove the rows which has the missing values more than 50 % like 'CP DL Retrans. Vol (Bytes)', 'TCP UL Retrans. Vol (Bytes)', 'Nb of sec with 37500B < Vol UL'.

Filling the Missing values:
         For numerical data we can apply methods like mean,meadian,mode on columns 'Start ms', 'End', 'End ms' like this for the categorical data we can apply the methods like 'ffill', 'bfill', 'mode' on columns like 'Handset Manufacturer', 'Handset Type'.

User Overview Analysis:
    In this first we have caluclated top 10 manufatures and top 5 manufatures type after that we have caluclated top 5 handsets per top 3 handset manufacturer, and also we have find the number of xDR sessions, Session duration, the total download (DL) and upload (UL) data and also done univarite bivaraite analysis on 'Total UL (Bytes)' like this

User Engagement Analysis:
       For this we have find the top 10 customers per engagement metric,and run a k-means (k=3) to classify customers into
three groups of engagement.

Experience Analytics:
      In this we have remove the outliers and also checked how the data has been distributed, and also we have find the Average TCP retransmission, Average RTT,  Handset type.

Satisfaction Analysis:
      In this we have find the average of both engagement & experience scores as the satisfactionscore & report the top 10 satisfied customer and also  Run a k-means (k=2) on the engagement & the experience score.
    
