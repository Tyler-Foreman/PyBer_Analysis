# Overview of PyBer Analysis

After creating a scatter plot and box-and-whisker plot for our employer, they have asked us to work on another visualization of the ride-share data for PyBer. Management is looking for us to generate a multiple-line graph summary of total weekly fares by each city type.

# Results

As we pulled together all of the data for the new summary our management has asked for, we built out a dataframe that shows the total of rides, drivers, and fares for each city type. We also calculated the average fare per ride and average fare per driver, as seen in the image below.

!['Pyber Summary'](/analysis/pyber_summary.png 'Pyber Summary')

In review of this compiled data we can see that the Rural city type is not a great source of revenue for PyBer. There is very low demand in rural cities, even though the average ride per fare is the largest of the city types. The suburban city type is generating about 30% of the fare revenue and 26% of the total rides for PyBer. The average fare per ride is nearly $31 per ride in the suburban city type. 

The urban city type is clearly generating the most revenue for PyBer, accounting for nearly 63% of their revenue. The urban city type rides are nearly 69% of their trips. There are significantly more drivers in the urban city type than there are rides, as there are approximately 1.5 drivers for every ride.

We would expect that due to the area density of these city types that the overall fare revenue will increase as there are greater chances for customers to request rides. When we summed all of the fare revenue by city type, we created a line chart to plot out this weekly revenue as seen in the graph below. Our expectation was confirmed after reviewing the line chart we created mapping out each city type.

!['PyBer City Type Weekly Revenue Line Chart'](/analysis/PyBer_fare_summary.png 'PyBer City Type Weekly Revenue Line Chart')

# Summary and Recommendations

After completing the analysis for PyBer ride data, there are a few recommendations that we would make to management at PyBer.

- As we seen a great disparity in the number of rides across each city type, it is our recommendation that PyBer management look to market their company further in rural and suburban city types to increase the number of rides. These city types are generating $6-10 more revenue per ride than the urban city type rides, so if ride volume increases in these areas it could benefit the businesses bottom line greatly.

- We see there is a signifcant disparity between the average fare per driver between the urban city type and the rural/suburban city types. The reason for this is there are nearly 1.5 drivers for every ride in the urban city type. PyBer should look further into if they have too many drivers in the urban area, or they need to heavily market in the urban area to generate more rides.

- The final recommendation for PyBer is to look into how they are defining each ride and city type. It is common for rides to go from a suburban area to an urban area (or vice versa), however there is no data to indicate a starting and end point for each ride. Based on this common experience, some of our data could be misconstrued as one city type or the other and not telling the full story for PyBer. We would recommend furthering this analysis to define the starting and end points for each ride to properly understand revenue between all city types and how many rides are going between each.