### python_api_challenge

#### In order to run the Jupyter Notebook, the Openweather and Google Maps API keys must be provided. The api keys used in the project have not been published for security reasons. 


**Main Observations / Insights**

The saved figures from the plots have been incorporated into these observations insights for explanatory purposes and legibility.
 
**1.	The most noticeable trend for the cities generated by the random sampling is that: -**

* 67% of the cities sampled are in the Northern Hemisphere, and, 
* 33% of the cities sampled are in the Southern Hemisphere.
* This is nearly identical to the land masses of the respective Hemispheres.
* 68% of the earth’s land mass is in the Northern Hemisphere, and,
* 32% of the earth’s land mass is in the Southern Hemisphere.
* Reference: https://www.worldatlas.com/articles/which-hemisphere-has-the-largest-area-covered-by-land.html
* This confirms that the cities sampled are distributed relatively uniformly by latitude as the sampled cities conform almost exactly with the land masses of the hemispheres.

**2.	Analysis of World-Wide Latitude versus Temperature reveals the following trends: -**

![image](https://user-images.githubusercontent.com/89948865/148723293-6062318d-82e1-42fb-a69e-30a1f7374743.png)

1)	Temperature tends to increase almost linearly as you move from the most northern latitudes towards the equator then plateau out once you reach 23 degrees (the Tropic of Cancer). 
2)	The cities sample was taken in the Southern Hemisphere summer (Northern Hemisphere winter) hence: -
* The temperate zone between the Tropic of Capricorn (-23 degrees) and the Equator (0 degrees) is experiencing hot summers conditions, 
* The temperate zone between the Tropic of Cancer (23 degrees) and the Equator (0 degrees) is experiencing cool winter conditions.
3)	The tropics of Capricorn and Cancer are the latitudes where the sun is closest to the earth in the respective summers which would account for the plateauing of high temperatures at this level in the Southern Hemisphere.
4)	The r squared value of 0.88 for the Northern Hemisphere shows a strong degree of fit to the line of best fit indicating a strong relationship between latitude and temperature [Refer point 2.1) below].
5)	Interestingly, the r-square value of 0.37 rounded shows that there is a relatively low degree of fit to the line of best fit for latitude and temperature in the Southern Hemisphere [Refer point 2.2) below].
6)	This may be explained by the sample size of 184 for the Southern Hemisphere versus the sample size of 378 for the Northern Hemisphere. Further statistical analysis beyond the scope of this assignment is required to explore this further. 

**2.1)	Linear Regression - Northern Hemisphere cities' Temperature vs Latitude**

![image](https://user-images.githubusercontent.com/89948865/148723349-19d6ec98-8a26-4933-8e62-9f04d9d66779.png)

The r-square is -0.875522577935197

* The linear regression plots Northern Hemisphere cities' temperatures against their latitude.
* The regression shows that temperatures are higher near the equator and lower further away from the equator.
* The r-square value of -0.88 rounded shows that there is a strong degree of fit to the line of best fit for latitude and temperature.

**2.2)	Linear Regression - Southern Hemisphere cities' Temperature vs Latitude**

![image](https://user-images.githubusercontent.com/89948865/148723387-15ccb019-ada3-4b2d-a9bb-2ddab18d1e5a.png)

The r-square is 0.3681140053502776

* The linear regression plots Southern Hemisphere cities' temperatures against their latitude.
* The regression shows that temperatures are higher near the equator and lower further away from the equator.
* The r-square value of 0.37 rounded shows that there is a relatively low degree of fit to the line of best fit for latitude and temperature in the Southern Hemisphere.

**3.	Analysis of World-Wide Latitude versus Humidity reveals the following trends: -**

* There does not appear to be any particular correlation between latitude and humidity on a world-wide comparison [Refer point 3.1) below].
* The r squared value of 0.88 for the Northern Hemisphere, however, shows a strong degree of fit to the line of best fit indicating a strong relationship between latitude and temperature [Refer point 3.2) below].
* Interestingly, the r-square value of 0.37 rounded shows that there is a relatively low degree of fit to the line of best fit for latitude and temperature in the Southern Hemisphere [Refer point 3.3) below].
* Again, this may be explained by the sample size of 184 for the Southern Hemisphere versus the sample size of 378 for the Northern Hemisphere. Further statistical analysis beyond the scope of this assignment is required to explore this further.

**3.1)	World_Wide cities' Humidity vs Latitude**

![image](https://user-images.githubusercontent.com/89948865/148723494-7ba248cb-cdc5-4ff7-8037-411e51d163a7.png)

**3.2)	Linear Regression - Northern Hemisphere cities' Humidity vs Latitude**

![image](https://user-images.githubusercontent.com/89948865/148723564-76f3c4f7-acba-47dd-bfbc-39c7068b0c44.png)

The r-square is -0.875522577935197

**3.3)	Linear Regression - Southern Hemisphere cities' Humidity vs Latitude**

![image](https://user-images.githubusercontent.com/89948865/148723914-70c7602d-284e-48b5-b466-4ea840937fa8.png)

The r-square is 0.3681140053502776

* The linear regression plots Southern Hemisphere cities' humidity against their latitude.
*	The regression shows that humidity is higher near the equator and lower further away from the equator.
*	The r-square value of 0.37 rounded shows that there is relatively low degree of fit to the line of best fit for latitude and temperature.


**4.	Analysis of Google Maps Heat Map reveals the following trends: -** 


*	The Google Heat Map from the Vacationpy notebook shows the areas with high humidity values. [Refer figure below]
*	These are largely concentrated near coastlines and large bodies of water such as the Mediterranean Sea, the Black Sea, the Caspian Sea, Lake Baikal, and the Angara River complex in Russia.
*	This is due to the air in these regions having more evaporated water in it than elsewhere.
*	The UK Isles has a high concentration of humidity due to:
*     the effect of the prevailing Gulf Stream which emanates from the Gulf of Mexico and provides cooling conditions in summer and warming conditions in winter,
*     its position between the Atlantic Ocean which acts as a buffer and the Continent of Europe.
* This provides the UK with a relatively milder climate than its European neighbours and it is largely spared from widely fluctuating climatic conditions prevailing in the continents of Europe and Asia. 
 
 
![image](https://user-images.githubusercontent.com/89948865/148723984-64421396-f756-48ec-b2d0-b818460d1e25.png) 


* The hotel map has been added here to go with the humidity heat map. 
 

![image](https://user-images.githubusercontent.com/89948865/148829379-ee9de95e-d7d4-4b07-a1ce-094f2cf765bf.png) 


* The map shows the 5 hotels that satisfied the ideal weather criteria 
*     1   mar del plata AR -38.0023 -57.5575 NH Gran Hotel Provincial
*     71  cape town ZA -33.925818.4232 The Bay Hotel
*     108 lompoc US 34.6391-120.4579 Hilton Garden Inn Lompoc
*     418 marana US 32.4367-111.2254
*     543 julio de castilhos BR-29.2269-53.6817Pousada Diana 


##Further Observations / Insights 


**5.	Analysis of World-Wide Latitude vs Cloudiness** 


![image](https://user-images.githubusercontent.com/89948865/148724164-a6212ef9-ed11-4347-8de4-2ad99481eb6d.png)

* There does not appear to be any particular correlation between world-wide latitude and cloudiness.


**6.	Analysis of World_Wide Latitude vs Wind Speed** 


![image](https://user-images.githubusercontent.com/89948865/148724259-a42648b9-b11c-49e9-8420-f7c23a0073ab.png)

* There does not appear to be any particular correlation between world-wide latitude and wind speed. 


**7.	Linear Regression - Northern Hemisphere cities' Latitude vs Cloudiness** 


![image](https://user-images.githubusercontent.com/89948865/148724337-e1cc42e3-808c-4f85-811a-8690c8eae417.png)

The r-square is 0.26688967231290295

*	The linear regression plots Northern Hemisphere cities' cloudiness (%) against their latitude.
*	There does not appear to be any particular pattern to the plot of cloudiness and latitude.
*	The r-square value of 0.27 rounded shows that there is relatively low degree of fit to the line of best fit for latitude and cloudiness. 


**8.	Linear Regression - Southern Hemisphere cities' Latitude vs Cloudiness** 


![image](https://user-images.githubusercontent.com/89948865/148724393-67170147-553a-4a21-b6ad-9dffc46f01e8.png)

The r-square is 0.32407428548748696

*	The linear regression plots Southern Hemisphere cities' humidity against their latitude.
*	There does not appear to be any particular pattern to the plot of cloudiness and latitude.
*	The r-square value of 0.32 rounded shows that there is relatively low degree of fit to the line of best fit for latitude and cloudiness. 
 

**9.	Linear Regression - Northern Hemisphere cities' Latitude vs Wind Speed** 


![image](https://user-images.githubusercontent.com/89948865/148724535-54e1f035-06d2-4abe-8b97-7d1d7dbfb438.png)


The r-square is 0.2064741086715493

*	The linear regression plots Southern Hemisphere cities' wind speed against their latitude.
*	There are some significant outliers between latitudes 30 and 60.
*	These are possibly due to the prevailing westerlies or anti-trade winds which operate in these latitudes, and which fluctuate wildly.
*	Further analysis needs to be done to prove or disprove this theory. This is beyond the scope of this assignment.
*	The r-square value of 0.21 rounded shows that there is relatively low degree of fit to the line of best fit for latitude and wind speed. 


**10.	Linear Regression - Southern Hemisphere cities' Wind Speed vs Latitude** 


![image](https://user-images.githubusercontent.com/89948865/148724588-da4e963d-fcfa-4026-a162-2d5df9fa4912.png)

The r-square is -0.3666007229034961

*	The linear regression plots Southern Hemisphere cities' humidity against their latitude.
*	There does not appear to be any particular pattern to the plot of wind speed and latitude.
*	 The r-square value of -0.37 shows that there is a low degree of fit to the line of best fit for latitude and wind speed. 


**11.	Copyright** 


*	The citipy software was developed by Winston Chen and is used with his approval subject to the copyright conditions located at the following link: -
https://github.com/wingchen/citipy/blob/master/LICENSE.txt 


**12.	References:** 


*	The following references have been used for this assignment. 

*     World Atlas
*     https://www.worldatlas.com/articles/which-hemisphere-has-the-largest-area-covered-by-land.html

*     Sciencing
*     https://sciencing.com/what-are-the-four-special-parallels-of-latitude-12517328.html

______________________________________________________________________________________________________________________________________________________________











