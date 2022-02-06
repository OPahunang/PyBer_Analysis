# PyBer_Analysis

## Overview of the analysis:

Pyber a ride-sharing company needs the captured 2019 data (city and ride data) for analysis and visualization. This will help the company to improve growth and services to the community, as well easier access and affordability to underserve cities.

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


-	The average fare per driver for each city type

-	A PyBer summary DataFrame


-	The PyBer summary DataFrame formatted 


### Deliverables 2: A multiple-line chart of total fares for each city type
-	DataFrame created using groupby() function with “type” and “date” columns with sum() method on the “fare” column

-	DataFrame created using pivot() function where the index is “date”, the columns are city “type” and “fare”

-	DataFrame created using the loc method on the range 2019-01-01 through 2019-04-28 

-	DataFrame created using resample() function in weekly bins and shows the sum of fares for each week

-	Line chart showing the Total fares by City Type and saved to the “Analysis” Folder
## Summary:
Recommendations to Pyber CEO according to figures and line chart provided
1)	Potential business growth to Rural cities, to add more drivers with the current drivers of 78 and average fare per driver of $55.49

2)	Accessibility and affordability to the community to review Rural cities average fare, with the $34.62 per ride compare to Urban with $24.53 per ride
3)	Balance the drivers count at Urban cities, where Total Rides of 1,625 and Total Drivers of 2,405, a lot of drivers not been fully utilized. 
