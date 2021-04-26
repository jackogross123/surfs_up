# Surfs Up Analysis
## Overview of the Analysis
W.avy is interested in opening up an ice cream and surf shop on the island of Oahu. One of the biggest issues with opening the shop though was to determine if there was suitable weather year round for both surfing and ice cream. I was asked to analyze temperature and percipitation patterns to determine if the island of Oahu had suitable weather conditions to support an ice cream and surf shop year round. For the challenge, I was asked to create a query that would pull the temperatures from all of the weather stations for June and December. If the weather is promising in both the peak of the summer and the winter than theres a high chance that the surf ice cream shop would do very well!

### Resources
Software: Jupyter Notebook, VS Code, sqlalchemy
[Data](https://github.com/jackogross123/surfs_up/blob/main/hawaii.sqlite)

## Results

![June_temps](https://github.com/jackogross123/surfs_up/blob/main/June_temps.png)

![Dec_temps](https://github.com/jackogross123/surfs_up/blob/main/Dec_temps.png)

The two images above show summary statistics for the temperatures in Oahu in December and June. The data sample starts in 2010 and comes from multiple weather stations on the island to capitlize on accuracy. Some of the key differences in the weather data are:

- The average temperatures in June is about 4 degrees warmer, however, the average temperature in December is 71 which is still warm enough for surfing and ice cream consumption.
- The minimum temperature in December is about 8 degrees coolder than the minimum temperature in June;
- However, the first quartile for December and June are only 4 degrees apart. This indicates that December is still suitable for surfing and ice cream.
- The 3rd quartile temperature for June is 77 and for December it is 74. 

## Summary 
I would reccomend to W.avy to make the investment in the surf and ice cream shop. As it can be seen from the challenges, the temperatures are suitable all year round to support the two activities of riding waves and eating ice cream. The average temperatures in June and December 75 and 71 which is warm enough to sit in the sun all year round. Additionally, the percipitation patterns are very favorable as it doesn't rain that much on the island of Oahu, from what we determined during our analysis. I think that an investment in an ice cream and surf shop is a great idea and will do very very well.

### Reccomendations
I think that two more important queries to build would be to determine the amount of cloud coverage there is on a given day for Oahu. It's very important the it be blue skies and sunny in order to get the most business. It would be valuable to calculate the amount of days that have clear skies and cloudy skies. I think that this would be a benefical study to look into.

Another important query to look into the wind speeds in June and December. I think that wind also adds a lot to temperature. If the weather is cloudy and windy than it actually may feel a lot colder than some of the coldest days in December. I think that once these two queries are conducted W.avy could make a decision of they wanted to invest in the shop.
