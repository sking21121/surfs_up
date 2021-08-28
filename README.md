# surfs_up

## Overview of Analysis
The analysis is to determine if the surf and ice cream shop business is sustainable year-round. The initial analysis was completed. Then W. Avy wanted the temperature data for the months of June and December in Oahu. In order to complete this analyis I will be using Python, SQLAlchemy, and Flask, to analyze and visualize climate data. 

## Results
The results come from the SQLite data given to me from W. Avy. I queried the Measurements table for the temperatures and filtered for the month of June and December. I put the results in a list and made a dataframe for each month. Then I printed out a summary for each month.

![june_temps](https://user-images.githubusercontent.com/86200136/131225152-5d978e87-44f6-4352-ae37-3f7961610d5b.png)
![dec_temps](https://user-images.githubusercontent.com/86200136/131225083-57054598-bf57-4da2-970d-048fc979e455.png)

From this data we can determine:
-there is not much of a difference in average temperature between June and December(74.9/71.0), about 4 degrees. 
-there is even a smaller difference in the max temperature between June and December(85/83), about 2 degrees.
-there is a larger seperation in the min temperatures  between June and December(64/56), 8 degrees.

### Summary
The data tells us the Surf and Shake shop should perform well in either month. Although June would perform better due to not so low temps compared to December. There will be days in December where the temp will get below 60 degrees, but on average it will stay above 70. 

If we compare the summaries of temperature and precipitation:


![J_D_temps](https://user-images.githubusercontent.com/86200136/131226115-52b083f7-68f3-487a-bb76-f5a82f44d174.png)
![J_D_Rain](https://user-images.githubusercontent.com/86200136/131226118-b0c56b3e-de82-4894-8782-cd28505170d2.png)


June reports less average rainfall compared to December(.14/.22). So still strong sales days for June because of high temperatures and not as much rainfall.
