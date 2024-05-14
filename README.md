The objective of this challegne is to integrate python and API skills to evaluate two scenarios:
  1. the relationship beteen weather vs latitude
  2. locating a hotel using the coordinates that represent your ideal weather situation based on the analysis conducted in No. 1, above.



Weather plots generated for No. 1 along and relationship analysis are below:
(Figures 1 through 4 show data without linear regression lines and can be found in the output data folder)
![Fig 5](/WeatherPy/output_data/Fig5.png)
![Fig 6](/WeatherPy/output_data/Fig6.png)

The two charts above, plot latitude vs. temperature for cities located in the northern hemisphere and southern hemisphere, separately. Both plots show a corrolation between temperature and latitude: the highest temperatures occur in cities that are closer to the equator (Latitude = 0), and the lowest temperatures generally occur in cities closer to the poles. the r-squared values are above 0.6, which is the strongest corrolation amoung the four relationships evaluated in this challenge.

![Fig 7](/WeatherPy/output_data/Fig7.png)
![Fig 8](/WeatherPy/output_data/Fig8.png)

The two charts above, plot latitude vs. humidity for cities located in the northern hemisphere and southern hemisphere, separately. The line and equation show little correlation between latitude and humidity, leaning toward higher humidities in the higher latitudes of the northern hemisphere and near the equator in the southern hemisphere.

![Fig 9](/WeatherPy/output_data/Fig9.png)
![Fig 10](/WeatherPy/output_data/Fig10.png)

The two charts above, plot latitude vs. cloudiness for cities located in the northern hemisphere and southern hemisphere, separately. The line and equation show no correlation between latitude and cloudiness in the northern hemisphere, and little correlation in the southern hemisphere, leaning towards greater percent cloudienss at the equator.

![Fig 11](/WeatherPy/output_data/Fig11.png)
![Fig 12](/WeatherPy/output_data/Fig12.png)

The two charts above, plot latitude vs. wind speed for cities located in the northern hemisphere and southern hemisphere, separately. The line and equation show no correlation between latitude and wind speed in the northern hemisphere, and little correlation in the southern hemisphere, leaning towards greater wind speeds at the equator.




The Map showing the location of the hotel in my ideal weather location, is below:
![Hotels in locations with ideal weather](/WeatherPy/output_data/Hotels.png)