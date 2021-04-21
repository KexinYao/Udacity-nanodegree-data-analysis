# Global Weather Trend 
In this project, I analyzed Berlin and global temperature data and compare the temperature trends of Belin to overall global temperature trends.



### Used SQL to extract the data from the database

Export the temperature data of Berlin and the world by write SQL query and open up the CSV file in Python.

### Create a line chart that compares Berlin temperatures with the global temperatures.

Created the line chart of the moving average temperature trend of Berlin and global separately as well as together by using the matplotlib and seaborn.


### Make observations about the similarities and differences of temperature average between Berlin and world 

Except the line chart can help us to find the differences, I used the numpy and pingouin to calculated the correlation between the temperatue and time and the observations are following:

* In general, the world's temperature is increasing with time, and the rate is becoming faster lately. But around 1820, there was a significant low temperature compare to other time.
* Berlin's temperature was also increasing with time and the rate also becoming faster lately.
* Compare the world's temperature and Berlin's temperature, as we can see,Berlin's Temperature is always higher than the world average temperature, and the gap was greatest around 1820.
* From the p value of the correlation coefficient, the temperature and the time have a strong correlation.


```python

```
