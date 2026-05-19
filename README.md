# morocco_electricity_consumption_analysis
This project is dedicated to analyzing time-series data of electricity consumption in Morocco in 2017 in three distinct zones.
The dataset used for this project is publicly available at [Maven Analytics](https://mavenanalytics.io/data-playground/morocco-electricity-consumption), and was originally downloaded from the UCI Machine Learning Repository.

After cleaning and analyzing data with Python and SQL, here are the insights I've found:
- Humidity has a reverse relationship with all other variables in the dataset, including power consumption in the three zones.
- Temperature and windspeed positively correlate with power consumption, though the relationship with temperature is stronger, with an average of around 0.42 for three zones.
- After the temperature reaches around 20 degrees Celcius, power consumption is more likely to rise sharply.
- In all three zones, power consumption reaches its bottom between 5-7 AM and reaches its peak at 8 PM.
- There are no significant fluctuations in power consumption on a weekly level.
- On an annual level, however, multiple differences come to mind:
  - Electricity usage in Zone 1 slowly climbed until August, then fell to levels below January at the end of the year.
  - Zone 2 experienced a similar climb until August, but recovered and roze again after a fall in September.
  - Zone 3 had the least stable trajectory of all: its power consumption rose sharply until July, then rapidly fell to 11000 kW/h in December - the lowest average monthly rate of all three zones.
 
Knowing these patterns, electricity providers can better adjust electricity consumption and supply to cut unnecessary costs and promote sustainable energy production.
