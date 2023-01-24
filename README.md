python-api-challenge

Open the Weather.Py folder to find the 2 jupyter notebooks and in the output_data folder inside Weather.Py you will find csv and plots:
  WeatherPy.ipynb
  VacationPy.ipynb

Part 1: WeatherPy

The cities.csv file in the Weather.Py folder was used for Requirement 1 and 2.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
  Fig.1 latitude and max temperature (C)
  Fig.2 latitidue and humidity (%)
  Fig.3 latitude and cloudiness (%)
  Fig.4 latitude and wind speed (m/s)

Requirement 2: Compute Linear Regression for Each Relationship

Compkleting this assignment encouraged me to gain a deeper understanding about thr r-squared value and what it is in a scatter, let's hope my application below is correct. I could have just spoke about weak or strong correlation, but thought I would try to go a little deeper. It was also interesting to have to make comparisons about latitiudes for southern and northern hemispheres and whether this correlation was near or far from the equator, made me think a little, scary!

  Fig.5 Northern Hemisphere: Temperature (C) vs. Latitude
The r-squared between North Hemisphere Latitude and Max Temperature (C) is: 0.7090162535951865. This value indicates that about ~71% of the values for the dependent variable, Max Temperature (C), are close to the regression line, showing a strong correlation i.e. as latitude increases North of the equator, Max Temperature decreases, which is an expected relationship.

   Fig.6 Southern Hemisphere: Temperature (C) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Max Temperature (C) is: 0.15845149747422807. This value indicates that about ~16% of the values for the dependent variable, Max Temperature (C), are close to the regression line, showing a small correlation i.e. as latitude increases South of the equator, Max Temperature decreases, which is an expected relationship.
  
  Fig.7 Northern Hemisphere: Humidity (%) vs. Latitude
The r-squared between North Hemisphere Latitude and Humidity (%) is: 0.14640045452866257. This value indicates that about ~15% of the values for the dependent variable, Humidity (%), are close to the regression line, showing a small correlation i.e. as latitude increases North of the equator, Humidity (%) increases. This was not what i would have expected as one would have thought there would be higher humidity near the equator.

  Fig.8 Southern Hemisphere: Humidity (%) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Humidity (%) is: 0.21538786041183416. This value indicates that about ~22% of the values for the dependent variable, Humidity (%), are close to the regression line, showing a small correlation i.e. as latitude increases South of the equator, Humidity (%) decreases. This is an expected relationship as one would expect there to be higher humidity near the equator.
  
  Fig.9 Northern Hemisphere: Cloudiness (%) vs. Latitude
The r-squared between North Hemisphere Latitude and Cloudiness (%) is: 0.07281549572384327. This value indicates that about ~7% of the values for the dependent variable, Cloudiness (%), are close to the regression line, showing a very weak correlation i.e. as latitude increases North of the equator, Cloudiness (%) increases. 

  Fig.10 Southern Hemisphere: Cloudiness (%) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Cloudiness (%) is: 0.23281977641178778. This value indicates that about ~23% of the values for the dependent variable, Cloudiness (%), are close to the regression line, showing a small correlation i.e. as latitude increases South of the equator, Cloudiness (%) decreases. 
  
  Fig.11 Northern Hemisphere: Wind Speed (m/s) vs. Latitude
The r-squared between North Hemisphere Latitude and Wind Speed (m/s) is: 3.425636091896652e-06. I am concerned there may be something wrong with the data or scipt for calculating r squared, due to the e-06 at the end of the value and it being greater than 1. Not sure why this is occuring.
 
 Fig.12 Southern Hemisphere: Wind Speed (m/s) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Wind Speed (m/s) is: 0.11301943936898567. This value indicates that about ~11% of the values for the dependent variable, Wind Speed (m/s), are close to the regression line, showing a small correlation i.e. as latitude increases South of the equator, Wind Speed (m/s) increases. 
  
Part 2: VacationPy

This was what was suggested:
Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
A max temperature lower than 27 degrees but higher than 21
Wind speed less than 4.5 m/s
Zero cloudiness
NOTE
Feel free to adjust your specifications, but make sure to set a reasonable limit to the number of rows returned by your API requests.

This was an interesting assignment, especially when we could adjust max temperatures, wind speed and cloudiness to narrow down the cities DataFrame and help with selecting an ideal Holiday Destination. I chose a Max temp>18 and <24 (I don't like HOT weather, strange, living in Perth), then a wind speed <4.5 m/s (Don't want to have my frizzy hair blowing in the wind and ruin my hairstyle) and 0 cloudiness.

With 10 cities, 8 with a hotel, I think I would choose to travel to:

Bella Union in Uruguay, as the humidity is a lot lower then other destinations, but Acapulco in Mexico would also be fun, and then Brazil.... decisions. Stick to the data, Uruguay it is.
The again I may need to check out the hotel website!

It is also interesting to see that list of city destinations:

Acapulco in Mexico
Pochutla in Mexico

Pisco in Peru
Torres in Brazil (Portuguese spelling)
Santa Maria in Brazil
Mar Del Plata in Argentina

Gat in Israel

Gasa in Palestine
Sohbatpur in Pakistan
