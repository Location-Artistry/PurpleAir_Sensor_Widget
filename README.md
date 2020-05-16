# PurpleAir_Sensor_Widget
This project has been substantially refactored and streamlined
Process to calculate AQI is now a function that is called multiple times
Greatly reduced lines of code and simplified project
5-16-2020

Simple Javascript widget using async function to query Purple Air json data and display stats for site
Performs calculation of AQI based on PM 2.5 readings.
Provides both the numeric index and narrative description.
Can loop through additional stations if added to sta_list[] array.
Purple Air has recently added the ability to query more than one station ID per url request through the API
This version is only basic text data, another repository includes mapping each station in leaflet.js
