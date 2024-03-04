
 # Bike Share Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/c0775050-d6bb-47db-84da-863feec173e0/ReportSection?experience=power-bi

## Problem Statement

This dashboard not only helps the management at Bike Share to see which are the peak months for bike rentals, the peak hours and the peak times for both casual and member riders but it also allows the management team to know their customers and their preferences. Also, the dashboard assists management in seeing which bikes are preferred to they can purhcase more of them.


### Steps followed 

- Step 1 : Download data from Kaggle.
- Step 2 : Extract files from zip file.
- Step 3 : Combine and transform the files in Power BI.
- Step 4 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 5 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 6 : Due to the fact that not all the columns are needed to satisfy the problem staement, a few columns were removed.
- Step 7 : For better naming conventions, rideable_type was change to Type of Bike, started_at was changed to Start Time, ended_at was changed to End Time,start_station_name was changed to Start Station, end_station_name was changed to End Station and finally, member_casual was changed to Type of Rider.
- Step 8 : The fields in the column 'Type of Bike' were capitalized by the first letter of each word, the '_' was replaced by ' '. Under the Type of Rider column, the fields were capitalized as well. 
- Step 9 : Both Start Time and End Time included both dates and times but an additional column was added, where the time only was extracted and the new columns were renamed Start Time and Date Time. For both Start Date and End Date, the format button was utilized and short date was selected.
- Step 10 : I chose 'close & apply'. 
- Step 11 : In order to figure out how many rides occurred between March 2021 and February 2022 the formula 'count' was used.
- Step 12 : Visuals were prepared to display the below;

  (a) # of rides by month and type of rider

  (b) # of rides by weekday and type of rider
  
  (c) # of rides by hour and type of rider
  
  (d) # of rides by type of rider
  
  (e) # of rides by type of bike
  
  (f) Start location by # of rides

  (g) End location by # of rides
  
  (h) A multi-row card was used to give a visual representation of the total # of rides, the number of member rides and the number of casual rides.

  13) A condtional formatting column was used from the Add column to filter the number of member riders and the number of casual member.
  
  14) A dates table was created whch would allow us to see the # of bikes by start hour.


Conclusion

For the casual riders, June, JUly, August and September 2001 were peak month where the rentals were high whilst, July, august, September and Octobe were high for member riders. This show that casual riders enjoy rinding in the summer more than the winter.

During weekends, more casual riders would go for a ride while the member riders would be consisten througoug the week. This implies that the member riders use the rentals as a regular mode of transportation but the casual riders would use it a time for relaxation on weekends.

The member riders would prefer to ride around 8am and 6pm while the casual riders would prefer to ride around 12pm and 5pm. Between 8am-6pm could indicate that the member riders use the bike to commute to and from work.

The preferred type of bike is the classic bike so the management should invest in more of these types of bicycles.

