# Data-Manipulation
QUT Unit 509 Project for R programming 

Data provided :<br />
southbrisbane-aq-2018: Daily weather observations in various cities in Australia from July 2008 until March 20191.<br />
weatherAUS.csv: South Brisbane (South East Queensland) 2018 hourly air quality and meteorological data2.<br />

Analysis required:<br />
a) Investigate whether there are any direct correlations between air quality indicators and either rain, humidity, wind, or temperatures. Explain what the correlations mean <br />
b) Use decision trees to see if at least one of the average daily air quality indicators can be predicted on the basis of any or all of the weather indicators provided. Explain what patterns the best decision tree highlights.<br />
c) Cluster the days and demonstrate through visualization how the clusters are organized. Explain what patterns they reveal.<br />

Driving question<br />
How does weather affect air quality in Brisbane, Australia?<br />


Report: air_quality.pdf


Code Structure

1. import the datasets <br />
2. clean up southbrisbane-aq-2018.csv <br />
  a. Step 1. Remove error/irrelevant data <br />
  b. Step 2: Deal with NA <br />
  c. Step 3. Check outliers. <br />
  d. Step 4: Check Data types  <br />
  e. Step 5: Remove Redundant variable <br />
3. clean up weatherAUS.csv <br />
  a. Step 1. Remove error/irrelevant data <br />
  b. Step 2: Check Data types  <br />
  c. Step 3: Remove Redundant variable <br />
  d. Step 4: Deal with NA  <br />
  e. Step 5: Merge features having data in 2 differnt timestamp.    <br />
  f. Step 6. Check outliers. <br />
4. Merge  2 datasets <br />
5. Corelation <br />
6. Decision Tree <br />
7. K-means Clustering <br />
        
