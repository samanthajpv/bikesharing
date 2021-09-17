# bikesharing

## Project Overview
The purpose of this project was to create a story using Tableau. The story showcases the NYC Citi Bike Data for August 2019 to show key stakeholders the potential of the business for expansion in other locations. Several visualizations were created to display insights and trends.

### Resources
- [NY Citi Bike Trip Data August 2019](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
- Software: Tableau, Jupyter Notebook
- Language: Python
- [Code for data type conversion](https://github.com/samanthajpv/bikesharing/blob/303f0decb2c21f59692c26afd56b90c19feed77c/NYC_Citibike_Challenge.ipynb)
- [Link to Tableau Story](https://public.tableau.com/app/profile/samantha.villanueva/viz/BikeSharing-NYCCitiBikeAugust2019Analysis/Story?publish=yes)

## Results
Before creating the visualizations, the a new column was created for 'tripduration' to be converted to a datetime data type. This was done using Python's ```to_datetime``` function. Below are the findings:

- **Top 10 Peak Hours** - The top 10 peak riding hours are highlighted to emphasize which hours are the busiest. After office hours, 5-6PM, has the most number of rides. It also gets busy in the morning, around 8-9AM as business hours start. These users are most likely those that commute to work.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/cc65593fc117960a589e5a675a683a7a96a6c685/Images/top%2010%20hours.png" width="500" height="400"/>
</p>

- **Top Starting and Ending Locations** - Most starting and ending locations are concentrated around mid to lower Manhattan area. There are also a handful of stations located in North of Brooklyn, West of Queens, and very minimal in Bronx.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/cc65593fc117960a589e5a675a683a7a96a6c685/Images/top%20locations.png" width="700" height="400"/>
</p>


- **Checkout Time for Users** - Most trip durations last under 20 minutes. As the trip duration gets longer, the number of rides get lower.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/checkout%20time%20for%20users.png" width="800" height="350"/>
</p>

- **Checkout Times by Gender** - Majority of the bike users are male. Most rides are still under 20 minutes with 5 minutes as the most common trip duration.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/checkout%20times%20by%20gender.png" width="800" height="350"/>
</p>

- **Trips by Weekday per Hour** - The darker color represents more rides. On weekdays, the number of rides are high during morning and evening rush hours. On weekends, the number of rides are more spread out from late morning up to 6-7PM.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/Trips%20by%20weekday%20per%20hour.png" width="400" height="450"/>
</p>

- **Trips by Gender (Weekday per Hour)** - The difference of this chart from the one above is that this emphasizes how much more male users there are. Peak hours are still the same.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/Trips%20by%20gender%20(weekday%20per%20hr).png" width="700" height="350"/>
</p>

- **User Trips by Gender and Weekday** - The heat map shows that the darker colors are seen under the row for subscribers. This is a good indication that there is a continuous demand for the service.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/User%20trips%20by%20gender%20and%20weekday.png" width="400" height="300"/>
</p>

## Summary

The August 2019 Citi Bike data shows that most users are male and are subscribers, the busiest stations are located in mid-lower Manhattan, majority of trip durations are under 20 minutes, and the largest portion of trips occur during rush hours. Below are two visualizations added as suggestions for future analysis:

- **Bike Utilization** - A modified version of the bike utilization from the module was created to represent the bikes that need maintenance/repair as well. The bubble chart easily separates the bikes that have exceedingly high trip durations which can be helpful to the business to assess bike performance as well.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/Bike%20utilization.png" width="800" height="500"/>
</p>

- **Station Traffic** - The visualization was created to highlight the stations that experience the most traffic. With this, the business will be able to strategize the quantity and placement of bikes among stations.
<p align="middle">
    <img src="https://github.com/samanthajpv/bikesharing/blob/699f4840e731044e2a51fab2052f5611b590cfb3/Images/Stations.png" width="600" height="350"/>
</p>

## Reference
(1) Trilogy Education Services. (2021, September). *Module 14 Challenge*. https://courses.bootcampspot.com/courses/626/assignments/13338?module_item_id=213431
