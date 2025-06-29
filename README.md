# Vehicles_US

Project Description

Fictitiously, I am an analyst at Crankshaft List. Hundreds of free vehicle advertisements are posted on the site every day. We will study the data collected over the past years and determine which factors influenced the price of a vehicle.
First, we will study how outliers influence various variables such as: price, vehicle age, date the advertisement was posted, etc.
Then, we will work with a filtered dataframe without outliers and use it as a basis to compare its results with the unfiltered dataframe.
Finally, we will analyze the number of advertisements and average price for each vehicle model and identify/study what influenced vehicle prices.

## Data Description
The dataset contains the following fields:

price
model_year
model
condition
cylinders
fuel — gasoline, diesel, etc.
odometer — the vehicle's mileage when the advertisement was published
transmission
paint_color
is_4wd — Whether the vehicle is 4-wheel drive (Boolean type)
date_posted — the date the advertisement was published
days_listed — days from publication until removal

### Columns created through analysis:

week_day, 
month, 
year, 
vehicle_age, 
mean_odometer
