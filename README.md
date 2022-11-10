# Jersey City Bike Rides 09/2021 - 08/2022

## Scope: 
Create Story for Jersey City CitiBiki Data Visualization from September 2021 to August 2022, 12 csv files

## Website to access the story: 
https://public.tableau.com/app/profile/phuongtieu/viz/Citibike202208_twbx/CityBikeRide?publish=yes

## Data Sources:
https://s3.amazonaws.com/tripdata/index.html

## Tools:
Tableau<br>
Jupyter Notebook (python)

## Data Preparation:
Split started_at, and  ended_at to create start_date and start_time, end_date and end_time.
Dropped started_at and ended_at.
Created new csv files.

## Data Analysis

### Two unexpected phenomina:

    - Saturday had least bike rides.
    - Top 1st start-station is JC005, also the top 1st end-station

### Story:
#### - Page1, 'Weekly Bike Ride' Saturday had least bike ride.  Sunday had lots bike rides
#### - Page2, 'User vs. Bike Type' docked_bike were used only by casual.
#### - Page3, 'Hourly Ride per year' 8am and 6pm were peak hour for the start-time.
#### - Page4, Top 7 start-stations are also top 7 end-stations. Bottom 10th end-station had very few rides.
#### - Page5, start-stations are mostly located at Jersey City.
#### - Page6, end-stations are majority located at the Jersey City, yet lots of bike ended up scatter around Central Park, Hudson Square and New York city.
