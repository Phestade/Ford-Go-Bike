# (FordGoBike System Data)
## by (Taiwo Olorunsogbon)


## Dataset


> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 
> The dataset contains 16 columns before I did cleaning. 
> Some attributes duration_sec, start_time, end_time, start_station_id, start_station_name, and member_age. I downloaded the data set from [HERE](https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1661450964706054&usg=AOvVaw19OjPQn0T98l3DjFpZtq_h)


## Summary of Findings

> I delete all user more than 60 years old because most users are between 18-60 year old (See findings exploration file for more details). Also I created new columns like age_category, duration_min, distance_km, start_time month, monthly, day, and hour. After I cleaned my data and created new columns the data became 179,882 records and 26 columns.


## Key Insights for Presentation

> Distribution of User Age: In the case of age, the distribution is more concentrated between 21 to 40 years old.
> I use a scatter plot to determine relationship or correlation between all the variables in the dataset.
> I then use multiple barcharts to introduce some of the other variables such as weekdays, age category, user type and gender.