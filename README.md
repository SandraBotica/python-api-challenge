# python-api-challenge

Open the Weather.Py folder to find the 2 jupyter notebooks and in the output_data folder inside Weather.Py you will find csv and plots:
  WeatherPy.ipynb
  VacationPy.ipynb

The cities.csv file in the Weather.Py folder was used for Requirement 1 and 2.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
  Fig.1 latitude and max temperature (C)
  Fig.2 latitidue and humidity (%)
  Fig.3 latitude and cloudiness (%)
  Fig.4 latitude and wind speed (m/s)

Requirement 2: Compute Linear Regression for Each Relationship

  Fig.5 Northern Hemisphere: Temperature (C) vs. Latitude
The r-squared between North Hemisphere Latitude and Max Temperature (C) is: 0.7143842653404553. This value indicates that about ~71% of the values for the dependent variable, Max Temperature (C), are close to the regression line, showing a strong correlation i.e. as latitude increases North of the equator, Max Temperature decreases, which is an expected relationship.

  Fig.6 Southern Hemisphere: Temperature (C) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Max Temperature (C) is: 0.2524701544605756. This value indicates that about ~25% of the values for the dependent variable, Max Temperature (C), are close to the regression line, showing a small correlation i.e. as latitude increases South of the equator, Max Temperature decreases, which is an expected relationship.
  
  Fig.7 Northern Hemisphere: Humidity (%) vs. Latitude
The r-squared between North Hemisphere Latitude and Humidity (%) is: 0.23974447029578033. This value indicates that about ~24% of the values for the dependent variable, Humidity (%), are close to the regression line, showing a small correlation i.e. as latitude increases North of the equator, Humidity (%) increases. This was not what i would have expected as one would have thought there would be higher humidity near the equator.
  
  Fig.8 Southern Hemisphere: Humidity (%) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Humidity (%) is: 0.0377121960940227. This value indicates that about ~4% of the values for the dependent variable, Humidity (%), are close to the regression line, showing a very wek correlation i.e. that as latitude increases South of the equator, Humidity (%) decreases. This is an expected relationship as one would expect there to be higher humidity near the equator.
  
  Fig.9 Northern Hemisphere: Cloudiness (%) vs. Latitude
The r-squared between North Hemisphere Latitude and Cloudiness (%) is: 0.034000362157100686. This value indicates that about ~3% of the values for the dependent variable, Cloudiness (%), are close to the regression line, showing a very weks correlation i.e. as latitude increases North of the equator, Cloudiness (%) increases. 

  Fig.10 Southern Hemisphere: Cloudiness (%) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Cloudiness (%) is: 0.18753173688897398. This value indicates that about ~19% of the values for the dependent variable, Cloudiness (%), are close to the regression line, showing a small correlation i.e. as latitude increases South of the equator, Cloudiness (%) decreases. 
  
  Fig.11 Northern Hemisphere: Wind Speed (m/s) vs. Latitude
The r-squared between North Hemisphere Latitude and Wind Speed (m/s) is: 4.916231650054034e-05. I am concerned there may be something wrong with the data or scipt for calculating r squared, due to the e-05 at the end of the value and it being greater than 1. 
  
  Fig.12 Southern Hemisphere: Wind Speed (m/s) vs. Latitude
The r-squared between Southern Hemisphere Latitude and Wind Speed (m/s) is: 0.04273471151129801. This value indicates that about ~4% of the values for the dependent variable, Wind Speed (m/s), are close to the regression line, showing a very weak correlation i.e. that as latitude increases South of the equator, Wind Speed (m/s) increases. 
 

