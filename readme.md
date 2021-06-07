# Ford GoBike System Data Exploration
## by Imesha Kuruppu


## Dataset

 Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. The Ford GoBike system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay, and San Jose. This dataset has data on the bike-sharing system collected in February 2019. The bike-sharing data set includes bike trip attributes(trip duration, station id, bike id, date) and user attributes(user type, gender, birth year). The dataset can download from the below link: https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv

## Summary of Findings

Initially, data wrangling was performed on the given dataset to get a cleaned dataset. Then exploration analysis was done to identify, times that bikes are high in demand, most frequent bike users characteristics, and average trip duration of users.
In univariate exploration, I investigated the distributions of individual variables such as user age, trip duration, etc. Outliers were removed from the user age column and only users 60 years old and younger are kept in the dataset. Trip duration data is right-skewed. Thus, a log-transformed graph is plotted and found the average trip duration of users. The number of bike rides by user type and gender were plotted. Bike usage during the week and each hour of the day was plotted. Bike usage at each station is plotted and found five most popular station ids and their names.

In the bivariate exploration, I investigated the relationship between pairs of variables. Plotted graphs to find bike usage trends during the week, during the day, and among user gender. Then average trip duration was plotted among each user type, user gender, and user age.

In Multivariate Exploration, I investigated three or more variables together.  Plotted graphs to find average trip duration during the week by each user type. Heat maps were created to find the average trip duration of each user type by user gender and age group. Then two heat maps were created to find subscribers and customers mostly used station id and time. Finally, heat maps were plotted to find the usage of the bike-sharing system on each hour during the week by subscribers and customers.

## Key Insights for Presentation

For the presentation, I focus to present how the average trip duration and bike usage demand vary with the user characteristics (ex: type, age, gender). I start by demonstrating in which percentage two user types use the bike-sharing system. Subscribers' usage is 90.4% while customers' usage is 9.6%.

Users' average trip duration investigation is started and initially found that the normal user average trip duration is around 10 mins. Then focus is given to find the average trip duration of each user type. (Customers' av. trip duration is higher than Subscribers'). When we consider the average trip duration of each user type during the week, we can find that during the week it has increased when compared to weekdays. Finally, average trip duration by age vs gender vs user type was plotted. The average trip duration is higher among younger and older users. Males have the lowest average trip duration. Other gender subscribers' have the longest trips on the other hand female customers' have the longest trips. But always customers' trip duration is higher than Subscribers'.   

Afterward bike usage trend was investigated. Initially found the demand according to the user gender. Males use the bike-sharing system most and then females, last is other gender users. When we consider bike usage patterns during the week by user type, we can find that customers' demand for bikes is less than Subscribers'. Subscribers' bike usage has dropped during the weekend. On the other hand, customers are using bikes on both weekdays and weekends. Finally, the bike usage trend was investigated of each user type in each hour during the week by age groups. Subscribers' bike usage is high from 7-9 am and 4-7 pm on weekdays. 50-65 aged users bike usage is low When compared to other users. Customers' bike usage is high from 7-9 am and 4-6 pm on weekdays and 10 am - 5 pm on weekends. 50-65 aged customers use bikes during the daytime of weekdays.  

It is interesting to find that, the users who use the bike-sharing system more frequently use it for shorter trips and users who use the bike-sharing system less frequently use it for longer trips.  
