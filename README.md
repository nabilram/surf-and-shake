# surf-and-shake

## Overview of the statistical analysis:

* Weather analytics for possible commercial/sales facility needed
    * Feasibility study of opening Surf and Ice cream shop in Hawauu
    * Weather as a major factor in startup based on client's previous experience
* Client has been provided annual weather analytics with specific station statistics
* Client is now asking for temp statistics for specific months (June and December)\
* Client has provided data in SQLite form

## Outcomes -- Preciptation in Jun vs. Dec
* Statistical analysis shows these three delta in temperate data b/w Jun and Dec
    * Max precipitation is higher in June by two units. 
        * This data aligns with Hawaii's monsoon season which begins in June
        * The islands' more dry seasons are indeed in December as well
    * Average precipitation (mean), however, is also in Dec than in June
        * Jun with 0.134 and Dec with 0.216
        * That is almost a 40% difference in averages
    * There are more weather datapoints to be found in Jun than Dec
        * Jun with 1574 datapoints and Dec with 1405
        * That is close to a 10% difference, which some may consider statistically significant

* June Weather Stats
![Jun_Weather_Stats](https://github.com/nabilram/surf-and-shake/blob/main/resources/june_temps.PNG)

* December Weather Stats
![Dec_Weather_Stats](https://github.com/nabilram/surf-and-shake/blob/main/resources/dec_temps.PNG)

        
## Summary of Results
* On average it rains more in June than in December.
* However, maximum precipitation is higher in December than in June.
* There are very few datapoints and more are needed to have a better analysis. 
    * ~10% difference in Jun vs Dec datapoints may be significant enough to warrant more data.