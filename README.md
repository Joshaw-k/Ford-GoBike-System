# Ford GoBike Data Exploration
## by Emefiele-konyeri Awinrin


## Dataset

The first three months of 2019 datasets were downloaded from a [baywheels-data](https://s3.amazonaws.com/baywheels-data/index.html) hosted on [AWS](https://s3.amazonaws.com/)(amazon web services), the three dataset were joined together has one dataset since they are of the same structure.

> This project has two main parts

1. In Part I, Exploratory data visualization, i used use Python visualization libraries to systematically explore this dataset(consists of information regarding 631,793 trips by the Ford Gobike system with 14 attributes columns), starting from plots of single variables and building up to plots of multiple variables.

> The Ford Gobike system data consists of 631,793 observations and 14 features('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'bike_share_for_all_trip'), after data cleaning the dataset was transformed to 482,555 observations and 23 features(additional features: 'start_neighbourhood', 'start_city', 'end_neighbourhood', 'end_city', 'distances(km)', 'start_date', 'start_hour', 'start_day', 'duration_min').

2. In Part II, Explanatory data visualization, i produced a short presentation that illustrates interesting properties, trends, and relationships that were discovered in my dataset. The primary method of conveying my findings were through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.


## Summary of Findings

* Subscribers are the major users of the Ford Gobike System, they use to mostly commute to their workplace on weekdays. While Customers spend longer duration of time on trips probably for recreation,visitation,fun places and all sort.
* The 'BikeShare For All ' program is a comprehensive bike share equity program, which includes equitable station siting, outreach, and discounted pricing to help expand transportation access to underserved communities. Only people registered to this program can use it, customers pay based on time spent on each trip that's why there was no count for customers using the 'BikeShare For All ' program
* Market St at 10th St station is the most popular station in terms of demand for bikes with close to 12,000 trips in the first quarter, it is located in a neighbourhood of Civic center and in a city of San Francisco, San Francisco seems to be the major city were Ford Gobike system is used with atleast 72% of the total trips of the Ford Gobike system in the city.
* Customers travel a farther distance from the start station than subscribers.
* During the weekends customers seems to be most users in demand for bikes with a concentration time around 10AM to 6PM while during weekdays subscribers seems to be the most in demand for bike at a conecentration time around 7AM to 9AM and 4PM to 6PM

## Key Insights for Presentation

For this presentation i will describe how a period of time(hour,day,month) could affect the duration of trips and demand for bikes, the distance different users cover from the start station to the end station, the geographical area where this bike system more popular and how well users use the 'Bikeshare For All' program