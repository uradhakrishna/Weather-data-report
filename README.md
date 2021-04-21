# Weather-data-report

# Summary 
This Python script allows to create a toy model of the environment (taking into account things like atmosphere, topography, geography, oceanography, or similar) that evolves over time. These measurements at various locations , currently considered the Australian stations, and the program emit that data, as in the following:

# Limitations & Considerations:
I have predefined the minimum and maximum values for Temperature, Pressure and Humidity  and also defined the Stations through which weather report will be generated.

Also, Predefined the Starting and ending dates will be considered for generating the Data.

# Expected Outcome
Station|GEO Location|Local Time|Conditions|Temperature|Pressure|Humidity

SYD|-33.86,151.21,39|2015-12-23T05:02:12Z|Rain|+12.5|1004.3|97

MEL|-37.83,144.98,7|2015-12-24T15:30:55Z|Snow|-5.3|998.4|55

ADL|-34.92,138.62,48|2016-01-03T12:35:37Z|Sunny|+39.4|1114.1|12


# Script Execution

Execute the following command to get functionality,

syntax : python3 gen_weather_data.py -i <path of the file>/<filename.tif> -r <ramdom station> (y/n)

python3 gen_weather_data.py -i /Users/uppugr1/workspace/weather-data/geo.tif -r y

# Generated sample data
uppugr1@C02W20PWHTD8 generate-weather-data-master % pwd
/Users/uppugr1/workspace/weather-data
uppugr1@C02W20PWHTD8 weather-data % head -10 weather_output_data.dat
BEN|33.9435602229,-117.641409054|2018-09-27 08:04:55|Snow|-5.2|949.5|59
HOB|33.9435602245,-117.640761244|2020-11-02 14:18:00|Sunny|39.6|859.5|56
CAN|33.9435602262,-117.640113434|2019-12-07 16:31:53|Rain|21.9|1023.9|56
DAR|33.9435602278,-117.639465625|2019-06-29 08:31:23|Rain|18.2|959.3|57
SYD|33.9435602295,-117.638817815|2019-12-18 14:27:15|Sunny|13.3|1168.3|61
MEL|33.9435602312,-117.638170006|2018-12-11 18:38:29|Snow|-5.4|944.9|61
ADL|33.9435602328,-117.637522196|2019-04-21 11:37:51|Sunny|36.6|960.9|69
ALB|33.9435602345,-117.636874387|2020-06-10 20:11:15|Snow|-5.9|1008.1|65
BRB|33.9435602362,-117.636226577|2018-03-27 01:45:01|Sunny|37.1|1160.8|57
PER|33.9435602378,-117.635578768|2020-02-24 02:28:01|Sunny|36.0|1192.1|59
uppugr1@C02W20PWHTD8 weather-data % 
