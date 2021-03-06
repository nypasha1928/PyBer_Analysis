PyBer ANALYSIS .



PROJECT OVERVIEW :

Analyze and visualize ride-sharing data using the power of Python, Pandas, and Matplotlib.
We've been given access to the company's complete recordset of rides. This contains information about every active driver and historic ride, including details like city, driver count, individual fares, and city type.

RESOURCES :

Data Source: city data.csv , ride data.csv
Software: Anaconda , jupyter .

DISCUSSION :

The PyBer Summary DataFrame provides an overview comparison of PyBer's ridesharing services in three types of cities: rural, surburban, and urban cities. Listed below there is a  bubble chart that show cases the average fare versus the total number of rides with bubble size based on the average number pf drivers for each city type : Urban, Suburban and Rural .

![image](https://github.com/nypasha1928/PyBer_Analysis/blob/main/analysis/Fig1.png)

The summary demonstrates that there is a larger demand for PyBer among riders in urban cities compared to suburban and rural cities. Between January 2019 and May 2019, there were 1,625 rides in urban cities, 625 rides in suburban cities, and 125 rides in rural cities. The figure below highlights how rides in Urban cities contributed the most to PyBer's overall rides during this five-month period.

![image](https://github.com/nypasha1928/PyBer_Analysis/blob/main/analysis/Fig6.png)

Creating a box-and-whisker plot (figure 2 below) showed us that there is one outlier in the urban ride count data ( 39 ). Also, the average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively.

![image](https://github.com/nypasha1928/PyBer_Analysis/blob/main/analysis/Fig2.png)

Given that there is a greater usage of PyBer in urban cities, the total fares are consequently also higher than suburban and rural cities. PyBer transactions in Urban cities totaled the highest whereas transactions in Suburban cities and rural cities followed respectively.
The figure below demonstrates where the majority of PyBer's revenue occurred during this time period: urban cities.

![image](https://github.com/nypasha1928/PyBer_Analysis/blob/main/analysis/Fig5.png)

In terms of costs, it appears that riders in rural cities pay on average almost $10 more for PyBer than riders in urban cities. The average fare per ride is about $35 in rural cities whereas the average fare per ride is about $25 in urban cities. Suburban cities' average fare per ride falls just in between - at about $31. While it may not be good news for riders in rural cities, it is a better market for drivers in this type of city. The average fare per driver is about $55 in rural cities, whereas the average fare per driver is about $17 in urban cities. Suburban cities' average fare per driver is about $40.

![image](https://github.com/nypasha1928/PyBer_Analysis/blob/main/analysis/PyBerSummaryDF.png)

The multiple-line chart "Total Fare by City Type" further supports the PyBer Summary DataFrame by providing trends of total fares in rural, suburban, and urban cities between January 2019 and April 2019. The yellow trend shows how fares in urban cities totaled from around $1,600 to $2,300 from beginning to end during this five-month period. In contrast, the blue trend shows how fares in rural cities totaled around $300 from beginning to end during the same time period. The orange trend shows how the total fares in suruban cities fall in between urban and rural cities: around $700 to $1,300 from beginning to end during this time. The chart further demonstrates similar peak times in all these types of cities. 

![image](https://github.com/nypasha1928/PyBer_Analysis/blob/main/analysis/Pyber_Challenge.png)


INFERENCE:

There is a larger use of PyBer ridesharing in urban cities.
There are more drivers in urban cities than rural cities.
As a result, the majority of PyBer's revenue occurs in urban cities.
On the other hand, the costs for using PyBer is greater among riders in rural cities than urban cities. 
Drivers in rural cities are earning more than drivers in urban cities. 
Overall, PyBer ridersharing services significantly differs in rural, suruban, and urban cities given the number of rides, drivers, and fares. Data supports that there is higher usage of PyBer ridesharing services in urban cities.
