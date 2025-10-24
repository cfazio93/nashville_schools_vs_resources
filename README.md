# Nashville Schools vs. Resources

## Table of Contents:
* [Project Overview](#project-overview)
* [Motivation](#motivation)
* [Initial Questions](#initial-questions)
* [Data Sources](#data-sources)
* [Limitations](#limitations)
* [Technologies Used](#technologies-used)
* [Analysis](#analysis)
* [Conclusions](#conclusions)
* [Next Steps](#next-steps)
* [Recommendations](#recommendations)
* [Dashboard](#dashboard)
* [Folium Map](#folium-map)

## Project Overview 
This project investigates the public resources (libraries, parks, bus stops, etc.) in the **Metro Nashville area**, and if there is a connection between available _resources_ in a neighborhood and that neighborhood’s _public school performance_. 

As a long-term resident of Nashville and teacher, I wanted to understand how resources may or may not impact student performance. As an educator, I am always interested in the nearby resources available so I can connect families to them. This project focuses on school performance data and Nashville location data.  

## Motivation 
My motivations and inspirations for this project come from my experiences growing up in NYC, and my recent experiences as a teacher the Nashville area.  

Growing up in New York City, public resources felt endless. There are over 200 public libraries, and several public transit options (NYC public school students are also given free access to transit). Since there are so many resources within walking distance, and it is so much easier to travel to resources that are further away, everything is more accessible. Students and families are not as confined to their neighborhoods, and not having to rely on a car makes a huge difference. 

In Nashville, almost everyone relies on a car, which makes accessing resources more difficult. There is also a discrepancy between school performance and income/poverty levels in the area. Additionally, there are differences in how students get to school. Some schools offer buses, but if students choose an ‘option’, charter, or magnet school, they are often responsible for getting to school themselves. 


## Initial Questions 
1) How did MNPS schools perform in the 2023-2024 school year?
2) How many public resources (libraries, parks/community centers, bus stops) are there in the Metro Nashville area?
3) How close are schools to public resources? What is each school's 'resource score'?
4) _Is there a connection between a school's performance and its proximity to these public resources?_

## Data Sources

### <ins>School Performance Data</ins> 
All of the _School Performance Data_ came from the [TN Dept. of Education website](https://www.tn.gov/education/districts/federal-programs-and-oversight/data/data-downloads.html)   

	- ACT Data (School-level 2023-24) 

	- English Language Proficiency Assessment (2023-2024, School Level)

	- Graduation Cohort Data (2023-24, School)

	- School Letter Grade (2023-24 A-F Letter Grade File) 

	- TVAAS Composites (2023-24 Composite) 


Additional School Data (current as of 9/2025) 

	- [School Locations](https://www.arcgis.com/home/item.html?id=a25c1ef058a247cfa2636a396f3aaedd#data)
	- [TN Dept. of Education High-Poverty Schools](https://www.tn.gov/content/dam/tn/education/esser-planning-resources/High_Poverty_Schools_TN_2021-07-30.pdf): I used this list to create a list of 'high-poverty' schools in MNPS to use on Python. _Note_ the most recent data I could find was from 2021. 

### <ins>Nashville Resources and Geographical Data</ins> (current as of 9/2025)  

	- [Bus Stop Locations](https://www.wegotransit.com/contact-us/developer-data-requests/ "Data request required")
	- [Library Facilities](https://data.nashville.gov/datasets/library-facilities/about)  
	- [Parks Facilities](https://data.nashville.gov/datasets/park-facilities/about)
	- [Zip Code Boundaries](https://data.nashville.gov/datasets/zip-code-boundaries-1)


## Limitations:
	-One major limitation was that I was unable to locate a downloadable dataset that contained the locations of MNPS schools. I used the 'School Locations' table and entered the information manually on my schools info XLSX file.  

## Technologies Used: 
-Excel: The original data was from XLSX and CSV files. After cleaning and exploring on Python, I also returned to Excel for some final cleaning/spot-checking.

-Python: I spent most of my time cleaning and exploring the data in Python.

-PowerBI: After cleaning the data, I uploaded my final XLSX file to PowerBI to create a dashboard. 


## Analysis 

## Conclusions 

## Next Steps

## Recommendations 

## Dashboard 

## Folium Map
Check out my interactive map! Use it to locate schools, libraries, parks/community centers, and bus stops. https://github.com/cfazio93/nashville_schools_vs_resources/blob/main/visuals/nashville_map.html
