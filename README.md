##NAME:

bike_sharing


## OBJECTIVE:

This open source project / package is created specifically for an assignment for the Advanced Python class of the Master in Big Data and Business Analytics at IE School of Human Sciences and Technology (Madrid). The objective is to rewrite the Bike Sharing analysis done in the Python for Statistical Programming subject using Dask data structures and ecosystem instead of plain pandas.

## CONTEXT:

Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back to another position. Currently, there are about over 500 bike-sharing programs around the world which are composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.

Apart from interesting real-world applications of bike sharing systems, the characteristics of data being generated by these systems make them attractive for the research. Opposed to other transport services such as bus or subway, the duration of travel, departure and arrival position is explicitly recorded in these systems. This feature turns bike sharing system into a virtual sensor network that can be used for sensing mobility in the city. Hence, it is expected that most of important events in the city could be detected via monitoring these data.

This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system in Washington, DC with the corresponding weather and seasonal information.

## CONTENT:

Both hour.csv have the following fields, except hr which is not available in day.csv.

1. instant: Record index
2. dteday: Date
3. season: Season (1:springer, 2:summer, 3:fall, 4:winter)
4. yr: Year (0: 2011, 1:2012)
5. mnth: Month (1 to 12)
6. hr: Hour (0 to 23)
7. holiday: weather day is holiday or not (extracted from Holiday Schedule)
8. weekday: Day of the week
9. workingday: If day is neither weekend nor holiday is 1, otherwise is 0.
10. weathersit: (extracted from Freemeteo)     
    a: Clear, Few clouds, Partly cloudy, Partly cloudy         
    b: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist         
    c: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds         
    d: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog      
11. temp: Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
12. atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
13. hum: Normalized humidity. The values are divided to 100 (max)
14. windspeed: Normalized wind speed. The values are divided to 67 (max)
15. casual: count of casual users
16. registered: count of registered users
17. cnt: count of total rental bikes including both casual and registered

##FUNCTIONALITIES:

The library contains these basic functionalities with the necessary tests:

1. 
2.
3.

##INSTALLATION:

##SUPPORT:

For questions about installation or any other remarks, please find below the email adresses of the creator of this library:

	- Pravat Pasayat : pasayat.pravat@student.ie.edu


##CONTRIBUTING:

How to contribute to our project: 

	* Fork the master repository (https://github.com/pasayatpravat/bike_sharing.git) to your github remote account
 
	* Clone the master repository to your local machine.
		git clone https://github.com/pasayatpravat/bike_sharing.git
	
	* Go to the local github directory.
		cd <directoryPath>
		
	* Add your fork as a remote
		git remote add <GitHub_UserName> <Forked_repository_URL>
		
	* Initialize the repository
		git init
		
	* Create a new branch 
		git checkout -b <branchName>
		
	* Add/Modify/Remove files in the repository.
	
	* Commit your changes.
		git add <filePath/fileName>
		git commit -m <"comment">
		
	* Push up your changes/branch to your forked repository. 
		git push <GitHub_UserName> <branchName>
		
	* Go to your GitHub remote repository and create a pull request.


##AUTHOR:

	- Pravat Pasayat
	

##ACKNOWLEDGMENTS:

We would like to thank our 'Advance Python' Professor, *Mr. Juan Luis Cano*, for his entertaining way of teaching classes and for helping us to understand what Python is all about. He was the one with this amazing idea of creating a new Python library and thanks to him, we now know more about how development works. 
