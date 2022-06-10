# python-api-challenge

### Data Analysis:

1. Observable trend: The maximum temperature of a city tends to decrease the further north that city lies from the equator.</br> There is a strong negative correlation between a city's positive degree of latitude (above the equator) and its maximum temperature on June 3rd, 2022 (the r value was -0.81). The r<sup>2</sup> value (0.66) shows that a city's positive degree of latitude accounts for 66% of the variation in that city's max temperature on June 3rd.
   <img src="https://github.com/mbruns13/python-api-challenge/blob/main/output_data/northern_lat_temp_plot.png?raw=true"
     alt="Scatter plot of City Latitudes (>=0) and Max Temperature on 6/3/22"
     style="float: left; margin-right: 10px;" />
2. Observable trend: The maximum temperature of a city tends to increase the further south that city lies from the equator.</br>There is a strong positive correlation between a city's negative degree of latitude (below the equator) and its maximum temperature on June 3rd, 2022 (the r value was 0.82). The r<sup>2</sup> value (0.68) shows that a city's negative degree of latitude accounts for 68% of the variation in that city's max temperature on June 3rd.
   <img src="https://github.com/mbruns13/python-api-challenge/blob/main/output_data/southern_lat_temp_plot.png?raw=true"
     alt="Scatter plot of City Latitudes (<0) and Max Temperature on 6/3/22"
     style="float: left; margin-right: 10px;" />
3. There is a very weak or no correlation between a city's latitude and its cloud coverage. When looking at plots of cities in both the [northern](output_data/northern_lat_cloudiness_plot.png) and [southern](output_data/southern_lat_cloudiness_plot.png) hemispheres, correlation coefficients were very low (0.045 for northern hemisphere and 0.063 for southern hemisphere)

