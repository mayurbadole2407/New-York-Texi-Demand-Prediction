# New-York-Texi-Demand-Prediction

There are roughly 200 million taxi rides in New York City each year. Exploiting an understanding of taxi supply and demand could increase the efficiency of the city’s taxi system. In the New York city, people use taxi in a frequency much higher than any other cities of US. Instead of booking a taxi by phone one day ahead of time, New York taxi drivers pick up passengers on street. The ability to predict taxi ridership could present valuable insights to city planners and taxi dispatchers in answering questions such as how to position cabs where they are most needed, how many taxis to dispatch, and how ridership varies over time. Our project focuses on predicting the number of taxi pickups given a one-hour time window and a location within New York City.

## Objective:
Giving a location and the time of the pickup,we have to predict the no of pickups as accurately as possible in that location and nearby location. Based on the data, machine learning model predicts the pickup demand of texis in 10 minutes time interval.

### Input:
Giving the time and location of the pckup..
### Output:
Prediction of number of pickups in a given time interval

# Performance Metrics:
Here we are using mean absolute precentage error metric which is best suitable for this busines problem.
### Mean Absolute Percentage Error:
suppose we predict 50 pickups in a specific region and our actual pickups are 52 so the difference is 2, we cannot say that the difference 2 we have to conclude it into the absolute precentage. So we have minimize this relative precentage error.
![image](https://user-images.githubusercontent.com/57489494/152691848-7c95afe4-e492-4c3f-bc70-bb0b5b028ce9.png)


## Dataset:
we generally tke ready made dataset from the kaggle but here, we extract data from the new york texi portal datastet is in csv files. Source => https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page we are using yellow texis data for our model building. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.
