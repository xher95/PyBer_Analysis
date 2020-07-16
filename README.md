# PyBer_Analysis
- Python 3.7
- Anaconda 4.8
- Jupyter Notebook 6.0

Import CSV files city_data.csv and ride_data.csv

Inspect data and load and read to PandasDataFrames

## Bubble Chart for Ride-sharing Data
- Create dataframes for each type of city
- Get the number of rides and average fare for each ity type
- Create bubble charts and a bubble chart for all cities

## Calculate Summary Statistics
- Sumaary statistics for number of rides, fare, and number of drivers by city type
- Create box-and-whisker plots

## Pie Charts: Percentage of Total Fares, Total Rides, Total Drivers by City Type
- Calculate the percentages
- Create pie charts for the percentages


# Challenge
## Purpose/Reason
Technical Analysis Deliverable 1 summarizes ride and fare data by city type making it easy to read. Technical Deliverable 2 shows a multi-line chart of average fare throughout the months by city type. The chart helps visualize total fare from each city type. This helps us to see which city type has the highest and lowest total fares and how it increase and decrease throughout the months.
## How the data was analyzed
-To analyze the data you have to consider the total for rides, drivers, and fares per city type. Using the groupby() function you can calculate all those values by city type.
- Using matplotlib and pandas you can create a DataFrame for already derived data. The .rename() fucntion allows for us to rename our pyber_data_df and .set_index() allows us to set our index to date as datetime data type. By using the object-oriented interface we import the style from matplotlib and use the FiveThirtyEight graph style to visualize our newly found database.
## What can be said about the summary DataFrame and multiple-line graph
- The summary DataFrame basically sums up the values and simplifies it for quick read and overview. You can sum up that in rural cities people ride less due to the high fare prices as compared to urban cities.
- The line graph helps you visualize the summary DataFrame in a whole. You can automatically see the comparison as the rate of total fares changes throught the year per city type and where the ride rate is the lowest and which is the highest.
## Summary of the results
Due to high average ride rates in Rural cities the total rides is a lot less than that of Urban cities.
- In rural cities, the total rides is 125 with a total Fare of $4,327.93 for an average fare per ride of $34.62.
- In suburban cities, the total rides is 625 with a total fare of $19,365.33 for an average fare per ride of $30.97.
- In urban cities, the total rides is 1,625 with a total fare of $39,854.38 for an average fare per ride of $24.53.

## Challenges and Difficulties
There was a bit of issue with creating the pivot table for the data. Watch out for typing errors and spelling. There was the issues with formatting the summary DataFrame because of punctuation errors. Plotting the FiveThirtyEight graph was very confusing. It was a challenge to use the right functions as you have to fix erros and look up howtos. Uploading the challenge section became a major issue on GitBash. I was receiving so much error with all the functions that I was limited to using or taught to use on the command window itself.
Stack Overflow to troubleshoot everything. Reference from other data scientists to fix errors and issues. Google everything up and always doublecheck spelling and typos.

## Recommendations and Additional Analyses
Considering the city types and their usage of the transportation method, maybe average out a fare price and total amount of necessary drivers so that the disparities among the city types would decrease. Depending on the condition and necessity of needing the transportation method, there will be fewer riders in that city type compared to where it is more of a necessity. We can probably generate a bar chart to check the rate of rides per city type and look at the data for every city per city types.
