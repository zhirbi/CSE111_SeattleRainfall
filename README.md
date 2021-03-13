# Seattle Rainfall Database Project
A database app that tracks Seattle's weather.
<br/><br/>


# Description
My partner Cristian and I chose this topic specificly because we were interested in some type of weather data set to work on, and we came across a Seattle data with plenty of entries and decided to work on a database project based on Seattle's rainfall by creating some interesting queries of the data set onto an app medium. This project is a python command line app that uses SQLite to communicate with the databse. In its current state, the time range of the database ranges from Janurary 1st, 1948 to December 12, 2017. The app allows the users to get weather report data (rain percipitation, max and min temperature, whether it rained or not) related to Seattle's weather in various range of dates. Additionally there are seven other functions for the users that gather different stats: number of days with and without rain from 1948 to 2017, a specific day's data from every year, list the hottest and coldest user defined days, and last but not least modification, which includes deleting, updating, and adding.

# Demo
Performing an annual report that gathers the average percipitation, and temperature of a specific year, along with the total days that rained. In this example year 2015 was used.
<img width="1030" alt="Screen Shot 2021-03-12 at 19 23 38" src="https://user-images.githubusercontent.com/43301201/111017437-77856380-8368-11eb-9ae1-f8fefd725026.png">
<br/><br/>

Selecting option 5 will output a list or a single data ranging from 1948 to 2017 with the most or least rainy days. If list was defined the user will then be required to input the number of years they want on the list. In this example it is doing a list view of 2 years with the least amount of rainy days from 1948 to 2017.<br/>
<img width="769" alt="Screen Shot 2021-03-12 at 19 25 34" src="https://user-images.githubusercontent.com/43301201/111017482-badfd200-8368-11eb-9627-5e15c4de1752.png">




# Collaborator
This project was completed alongside:<br />
Cristian Galvan<br />
Computer Science and Engineering<br />
University of California, Merced<br />
https://github.com/Cristian54

# Sources
Data set was found on Kaggle: <br />
https://www.kaggle.com/rtatman/did-it-rain-in-seattle-19482017
