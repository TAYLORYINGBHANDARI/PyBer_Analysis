# PyBer_Analysis

- Use Python and Pandas library to analyze ride sharing data by city type. 
- Use Jupyter Notebook and Matplotilib  to visualize data outcomes as a mulitple-line graph.

## Overview of the analysis:

V.Isualize is asking to create a summary DataFrame of the ride-sharing data by city type. Creating a multiple-line graph to display the total weekly fares for each city type. summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

### completing tasks
    * Merge the city_data_df and the ride_data_df.
    * Get a Summary DataFrame¶
        1. Get the total rides for each city type
        2. Get the total drivers for each city type
        3. Get the total amount of fares for each city type
        4. Get the average fare per ride for each city type. 
        5. Get the average fare per driver for each city type. 
        6. Create and clean up a PyBer summary DataFrame. 
    * Create a multiple line plot that shows the total weekly of the fares for each type of city.¶
        1. create a new DataFrame showing the sum of the fares for each date where the indices are the city type and date.
        2. reset index
        3. Create a pivot table with the 'date' as the index,get the total fares for each type of city by the date. 
        4. Create a new DataFrame using loc on the given dates.
        5. Set the "date" index to datetime datatype.
        6. Get the sum of the fares for each week by creating a new DataFrame using "resample(W)"
        7. Plot the multiline graph


## Results:

 Pyber Ride summary by date
 
 
   ![image](https://user-images.githubusercontent.com/85265816/126076638-a83dfa2d-3f91-48b6-ac4d-ea1112f63884.png)


 Sum of the fares by week
 
    
   ![image](https://user-images.githubusercontent.com/85265816/126076654-782c91dd-0b45-4dba-b8ad-49a075838a2b.png)

 Total Fare by City Type multi-linegrapph
   
 ![image](https://user-images.githubusercontent.com/85265816/126076668-3d4e0962-1918-42bb-9073-2fefab39849f.png)
    


The datashows that the ride sharing business has a larger scale than suburban and rural cities.
There are higher amount of total rides count and higher amount of drivers. Especially Urban total rides is almost 12x more than rural area and Urban drivers are almost 31x more than rural area.
The Average Fare per ride and the Average Fare per Driver sits the lowest in urban cities, while the Urban city has the largest amount of Total Fares.  This indicates that Urban market is very competitive. Even though the urban city total fares are among the highest,each employee makes less on average compared to rural or suburban ones.

The Total Fare by City Type multi-linegrapph shows that all three city types follow a similar trends, and no intersection.
The yellow line shows Urban city make the most and had a slightly increase through out the year of 2019 compare with Suburban and rural city type.
The rural area are showing a steady trend but not much of growth, the Total Fare stayed under $500 each week.

# Summary

After analyzing both our DataFrame and Total Fare by City typke line Chart, we have come up with three main business recommendations.

1. Decrease drivers in Urban cities.
    There are more supply than the rides demand, that cause the average fare per drivers rates so low. Considering decrese the supple to increse driver's average income.

2. Increase drivers in rural citiese.
    Total rides to total driver ratio is 125:78=1.6:1. We can try to increse the driver amount to match with the market demands.

3. Making the supply market more flexible, flucuate to match the market demand and monitoring the changes for the future year.
    Eventhough there is no declining trend showing in the graph, however there are several down points in each city.If the CEO can make a flexible plan to deploy driver to the demanding cities weekly and also monitoring the upcoming year statistics. Hope we can see some increases in total fare and reducement of down points.


