# Data-Manipulation
QUT Unit 509 Project for R programming 

Data provided :
southbrisbane-aq-2018: Daily weather observations in various cities in Australia from July 2008 until March 20191.
weatherAUS.csv: South Brisbane (South East Queensland) 2018 hourly air quality and meteorological data2.

Analysis required:
a) Investigate whether there are any direct correlations between air quality indicators and either rain, humidity, wind, or temperatures. Explain what the correlations mean (you may use visualization if you wish).
b) Use decision trees to see if at least one of the average daily air quality indicators can be predicted on the basis of any or all of the weather indicators provided. Explain what patterns the best decision tree highlights.
c) Cluster the days and demonstrate through visualization how the clusters are organized. Explain what patterns they reveal.

Driving question
How does weather affect air quality in Brisbane, Australia?


Report: air_quality.pdf


Code Structure

1. import the datasets
2. clean up southbrisbane-aq-2018.csv
  a. Step 1. Remove error/irrelevant data
  b. Step 2: Deal with NA
  c. Step 3. Check outliers.
  d. Step 4: Check Data types 
  e. Step 5: Remove Redundant variable
3. clean up weatherAUS.csv
  a. Step 1. Remove error/irrelevant data
  b. Step 2: Check Data types 
  c. Step 3: Remove Redundant variable
  d. Step 4: Deal with NA 
  e. Step 5: Merge features having data in 2 differnt timestamp.   
  f. Step 6. Check outliers.
4. Merge  2 datasets
5. Corelation
6. Decision Tree
7. K-means Clustering
        
