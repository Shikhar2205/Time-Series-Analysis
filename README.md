# Time-Series-Analysis
This is the basic time series analysis using ARIMA. Use of ACF and PACF plots to determine the values of (p,q,d).
In this question we have to analyse the count of the people at any point of time inside a building.

## Data Set Information:  <br>

Observations come from 2 data streams (people flow in and out of the building), over 15 weeks, 48 time slices per day (half hour count aggregates). <br>

The purpose is to predict the presence of an event such as a conference in the building that is reflected by unusually high people counts for that day/time period. <br>


## Attribute Information:<br>

1. Flow ID: 7 is out flow, 9 is in flow <br>
2. Date: MM/DD/YY <br>
3. Time: HH:MM:SS <br>
4. Count: Number of counts reported for the previous half hour <br> 

Rows: Each half hour time slice is represented by 2 rows: one row for the out flow during that time period (ID=7) and one row for the in flow during that time period (ID=9) <br>

Attributes in .events file ("ground truth") <br>
1. Date: MM/DD/YY <br>
2. Begin event time: HH:MM:SS (military) <br>
3. End event time: HH:MM:SS (military) <br>
4. Event name (anonymized) <br>
