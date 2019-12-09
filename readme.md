# Data Visuzalitaion of baywheels trip data
This is one of the projects in the Data Analyst Nanodegree Program at Udacity. The main purpose of this project is to learn how to use the data visualization skills to explore the data I chose ant to tell the findings in a proper way. I analyzed the dataset of baywheels, a bike-share service by Lyft in the Bay Area. 

Please let me know if you find any mistakes.

## How to Use
1. Download this repository
2. Make a folder called "data".
3. Download the file, `201910-baywheels-tripdata.csv.zip` from [baywheels website](https://s3.amazonaws.com/baywheels-data/index.html) and put it in the data folder.
4. Run the Jupyter Notebook files.

## Summary of Findings
### The Number of Trips
I found that the three variables, day of the week, time of day, and user type, largely influence the number of trips. The usage pattern on weekdays is different from those on weekends. People commonly ride a bike in the morning and evening on weekdays and in the afternoon on weekends. These findings suggest that not only subscribers but also customers use this service for their commute. Moreover, subscribers mainly use this service on weekdays, but customers use it both on weekdays and weekends. 

### The Trip Duration
Through the exploration process, I found that the combination of day of the week, user types, and time of the day mainly decides the trip duration of users. One-time users on the weekend ride a bike more than 25 minutes on average, which is twice longer than the trips by subscribers on weekends and 38% longer than their usage on weekdays. When I consider this result that the travel time in the afternoon is longer than other times of the day on weekends, the one-time users rent a bike for sight-seeing or recreation.

## License 
The source code is released under the MIT License.