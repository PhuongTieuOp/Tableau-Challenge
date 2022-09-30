# Tableau-Challenge 

## Scope: Create Story for Jersey City CitiBiki Data Visualization from September 2021 to August 2022, 10 csv files

## Website to access the story: 
https://public.tableau.com/app/profile/phuongtieu/viz/Citibike202208_twbx/Story-Station?publish=yes

## Data Sources:
https://s3.amazonaws.com/tripdata/index.html

## Tools:
Tableau<br>
Jupyter Notebook (python)

## Data Preparation:
    - Split started_at, and  ended_at to create start_date and start_time, end_date and end_time.
    - Dropped started_at and ended_at.
    - Created new csv files.

## Data Analysis

### Two unexpected phenomena:

    - Saturday had least bike rides.
    - Top1 start-station is JC005, also the top1 end-station.

### Story Boards:

User Story:
    - Page1, 'Weekly Bike Ride' Saturday had least bike ride.  Sunday had lots bike rides
    - Page2, 'User vs. Bike Type' docked_bike were used only by casual.
    - Page3, 'Hourly Ride per year' 8am and 6pm were peak hour for the start-time.

Station Story:
    - Page1, Top 7 Start-station also almost by the top 7 of end-station. Bottom 10 End-station had very few rides.
    - Page2 and 3, Start-stations are mostly located at Jersey City.
    - Page4 and 5, End-stations had major located at the Jersey City, yet lots of bike ended up at Central Park, Hudson Square and New York city.
