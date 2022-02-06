# PyBer_Analysis

## Overview of the analysis:

Pyber a ride-sharing company, needs their 2019 city and ride data for analysis and visualization. This will help the company to improve growth and services to the community, as well easier access and affordability to underserve cities.

In this particular project using Python skills and knowledge of Pandas, need to create a summary dataframe of the ride-sharing by city type. Then, using Pandas and Matplolib to create a multiple-line graph that shows total weekly fares or each city type. Finally, a written report that summarizes how data differs by city type and how those differences can be used by CEO at Pyber.

## Results:

### Deliverables 1: A ride-sharing summary DataFrame by city type

-	The total number of rides for each city type

![Total_Rides_Count_City_Type.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/Total_Rides_Count_City_Type.png)


-	The total number of drivers for each city type

![Total_Drivers_City_Type.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/Total_Drivers_City_Type.png)


-	The sum of the fares for each city type

![Total_Amout_Fares_City_Type.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/Total_Amout_Fares_City_Type.png)


-	The average fare per ride for each city type

![Averag_Fare_Per_Ride_City_Type.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/Averag_Fare_Per_Ride_City_Type.png)


-	The average fare per driver for each city type

![Average_Fare_Per_Driver_City_Type.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/Average_Fare_Per_Driver_City_Type.png)


-	A PyBer summary DataFrame

![PyBer_Summary.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/PyBer_Summary.png)


-	The PyBer summary DataFrame formatted 

![PyBer_Summary_Formatted.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/PyBer_Summary_Formatted.png)



### Deliverables 2: A multiple-line chart of total fares for each city type

-	DataFrame created using groupby() function with “type” and “date” columns with sum() method on the “fare” column

![DataFrame_groupby_type_date.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/DataFrame_groupby_type_date.png)


-	DataFrame created using pivot() function where the index is “date”, the columns are city “type” and “fare”

![DataFrame_pivot.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/DataFrame_pivot.png)


-	DataFrame created using the loc method on the range 2019-01-01 through 2019-04-28 

![DataFrame_loc.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/DataFrame_loc.png)


-	DataFrame created using resample() function in weekly bins and shows the sum of fares for each week

![DataFrame_resample.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/DataFrame_resample.png)


-	Line chart showing the Total fares by City Type and saved to the “Analysis” Folder

![Total_Fare_by_City_Type.png](https://github.com/OPahunang/PyBer_Analysis/blob/main/Analysis/Total_Fare_by_City_Type.png)


## Summary:

Recommendations to Pyber CEO. according to figures and line chart provided

1)	Potential business growth to Rural cities, to add more drivers with the current drivers of 78 and average fare per driver of $55.49

2)	Accessibility and affordability to the community to review Rural cities average fare, with the $34.62 per ride compare to Urban with $24.53 per ride

3)	Balance the drivers count at Urban cities, where Total Rides of 1,625 and Total Drivers of 2,405, a lot of drivers not been fully utilized. 
