## 1. System name
Real Estate Analyzer
## 2. Motivation
### Why do you want to develop the system?
If one day I have enough capital, I would like to research the real estate market and invest in it. This type of investment can generate passive income.
### Why is the topic (or system) important?
Everybody is affected by the real estate market because everybody needs a place to live. This system allows for the user to analyze the market and make informed decisions.
## 3. Purpose
To develop a system that helps the user to analyze the real estate market.
### What are the main functions are... (OR solve what problem... )
* Display houses on a map
* Show the houses that have a higher yield/price 
* Show the houses that have a higher rent/price
* Show the houses that have a higher area/rent
## 4. Relative work
### What are relative systems and their functions?
* Get data from addresses
* Display houses on a map
* Show the houses that have a higher yield/price 
* Show the houses that have a higher rent/price
* Show the houses that have a higher area/rent
### What are the differences between the related systems with yours?
Other systems don’t tell you yield/price.
## 5. System description
### Developed packages (or modules) and tools
* Requests
* Bs4
* Matplotlib
* Zillow API
### System functions and main techniques
* Get data from addresses
* Display houses on a map
* Show the houses that have a higher yield/price 
* Show the houses that have a higher rent/price
* Show the houses that have a higher area/rent
### Describe the process of development
1.	Investigate about Zillow
2.	I tried getting home addresses from the website, but they detected that I was using special software and denied my website request. To bypass this security measure is beyond the scope of this course so I downloaded the html files manually.
3.	I collected the home addresses from the html files.
4.	Understand the Zillow API and how to request data.
5.	Made a class to manage information well.
6.	Made a list with all the requests I’ll make to Zillow.
7.	Get information from 726 houses.
8.	Get rental yield.
9.	Display graphs.
### How many hours do you spend on this system?
About 10 hours.
### What percentage have you developed by yourself for this system?
About 90%.
## 6. Conclusion and reflection
![alt text](https://github.com/elvis-suazo/real-estate-analysis-in-florida/blob/master/zestimate%20vs%20yield.png "zestimate vs rental yield")
A higher investment doesn’t suggest a higher return, in fact, the opposite seems to be true. The houses above the trendline have a better performance than average from an investment’s point of view. Further analysis is required for the outliers with very good yield/price.
