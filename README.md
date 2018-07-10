# Bikesharing-Predictions

Challenge is to help https://www.capitalbikeshare.com/system-data. We first divided the given excel file in train and test. We are required to predict the total count of bikes rented during each hour covered by the test set. Training data has 12 variables/feature that ought to help us. These are 

datetime:   date and hour in "mm/dd/yyyy hh:mm" format
season:     Four categories-> 1 = spring, 2 = summer, 3 = fall, 4 = winter
holiday:    whether the day is a holiday or not (1/0)
workingday: whether the day is neither a weekend nor holiday (1/0)
weather:    Four Categories of weather
            1-> Clear, Few clouds, Partly cloudy, Partly cloudy
            2-> Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
            3-> Light Snow and Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
            4-> Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp:       hourly temperature in Celsius
atemp:      "feels like" temperature in Celsius
humidity:   relative humidity
windspeed:  wind speed



In test set we can find only 9, 3 are excluded since that is exactly what we are trying to predict.
registered: number of registered user
casual:     number of non-registered user
count:      number of total rentals (registered + casual)
