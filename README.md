# PyBer_Analysis
## Overview
The purpose of this new analysis for the ride-sharing company PyBer was to build a new analysis
of the ride-sharing data by city type (urban, suburban, rural). Then using a new dataframe, build 
a multiple-line graph showing the total weekly fares for each city type. And finally using the new
analysis, summarize differences by city type, and make suggestions on how that data can be used
at PyBer.

## Results

                                                  Summary
![PyBer_fare_summary](https://github.com/HexHaunter/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png?raw=true)

As you can see from the chart above, urban cities had the highest total fare revenue ($39,854.38), 
followed by suburban ($19,356.33), and finally, rural ($4,327.93). This isn't surprising considering 
that urban cities have more than twice as many rides and drivers as the other two categories; 
urban cities had a total of 1,625 rides and 2,405 drivers,compared to suburban's 625 rides and 490 
drivers, and rural with only 125 rides and 78 drivers. However, when it came to finding the average
fare per ride and average fare per driver the order switched. The average fare per ride in urban cities was 
$24.53 and per driver was $16.57, in suburban it was $30.97 per ride and $39.50 per driver, and in 
rural it was $34.62	per ride and $55.49 per driver.


## Summary
Urban cities definitely make the most revenue in total, but not per ride or driver. This could
be because there were only 1,625 rides but over 2,405 drivers in urban cites, which means
prices have to go down to compete between the over-abundance of drivers. It might be 
worth looking into ways of either bumping up rider numbers to increase fare prices,
or cutting driver numbers. Another factor into fare prices is that with the current data it's 
unkown how far each driver has to take riders. In cities it could be mainly short trips, whereas
in rural areas it could be much longer distances, and therefore higher fares. It would be worth looking
into tracking how far drivers go per ride to account for this in future analysis. 
