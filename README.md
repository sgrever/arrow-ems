# arrow-ems

## Background 

In resource-limited, siloed organizations, data sharing is cumbersome, especially when departments must collaborate on complex analyses without a shared database system.

These instances inspired me to explore the possibilities of Apache Arrow. I utilized the following guides:  

* [R for Data Science Chapter 22: Arrow](https://r4ds.hadley.nz/arrow#getting-the-data) by Hadley Wickham 
* [Doing More With Data: An Introduction to Arrow for R Users](https://youtu.be/O42LUmJZPx0?si=ENeW8Ihz_BU8L2tG) by Danielle Navarro at Voltron Data  
* [Using the {arrow} and {duckdb} packages to wrangle medical datasets that are Larger than RAM](https://youtu.be/Yxeic7WXzFw?si=t4Dxvy-UdS__EUIf) by Peter Higgins at R Consortium 


## Data 

This project uses New York City dispatch calls data from 2007 to 2024. The **[EMS Incident Dispatch Data](https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj/about_data)** dataset contains 27M records detailing incident location, perceived call severity, and Fire Department response time.


## R Version

This project was produced with R version 4.3.1.
