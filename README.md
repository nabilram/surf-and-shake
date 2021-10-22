# surf-and-shake

## Overview:

* Temperature analytics for possible commercial/sales facility needed
    * Feasibility study of opening Surf and Ice cream shop in Hawaii
    * Temperatue is a major factor in startup based on client's previous experience
* Client has provided weather and temp data from 2010-2017
* Client is now asking for temp statistics:
    * For specific months in 2010-2017 time span (Jun and Dec)

## Temperature Data Obervations Jun vs Dec:
* Statistical analysis shows these observations in temp data b/w Jun and Dec
    * Min temp is much lower in Dec by 8 degrees
        * This aligns with December having cooler temperatures in general
        * From a busines ops standpoing, we should expect less activity as a whole
    * Max temp between Dec and Jun are close (only 3 degrees apart)
        * While it may get colder in Dec, max temps relatively remain the same
        * This bodes well for the business as there is warm weather all year round
    * There are more temp datapoints to be found in Jun than Dec
        * Jun with 1700 datapoints and Dec with 1517
        * That a difference of over 10%, which some may consider statistically significant

* June Temp Stats (session query + df.describe for quality check)
    * ![Jun_Weather_Stats](https://github.com/nabilram/surf-and-shake/blob/main/resources/june_temps.PNG)

* December Temp Stats (session query + df.describe for quality check)
    * ![Dec_Weather_Stats](https://github.com/nabilram/surf-and-shake/blob/main/resources/dec_temps.PNG)
        
## Summary of Results:
* On average it is warmer in June than in December
    * Business operations should be more robust in Jun than Dec
* Max temperatures in Jun and December are relatively similar
    * While business peaks in June, December will still have weather (high temps) that is conducive for business.
* TWO ADDITIONAL SUGGESTIONS FOR ANALYSIS:
    * Calculate and plot AVE TEMP PER DAY on each month. 
        * plot using histogram with 30 or 31 bins (representing each day)
        * This will inform the "best" day for business / surfing
    * Expand analysis to all months of the year recalculate using QUARTERLY cadence in dates
        * This will inform the business operations which quarter:
            * required more inventory, labor, and such. 
            * requires expansion or consolidation of operations due to demand (based on temps)