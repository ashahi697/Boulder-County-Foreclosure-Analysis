# Boulder-County-Foreclosure-Analysis
Analyzing foreclosure sale prices compared to assessed property values 


##Projecct overview:
Looking at the relationship between residential foreclosure sale prices and county assessed 
property values in Boulder County.

##research question
How much higher or lower are residential foreclosure properties sold for in comparison to assessed values by the county. I also want to see the variance by different cities within the county.


##Method
I am using python primarily for the language but within python I have been leveraging other libraries in python such as pandas, numpy, beautifulSoup, requests, and matplotlib. These are all being used to clean the data I will be getting from the boulder county assessors office.

Started by at first seeing if this data can be scraped. Since the county makes this data accessible I could just download the csv files. From there I put them all in the same folder and started my Jupyter notebooks. I downloaded the csv files called Sales.csv, Values.csv , Owner_Address.csv. These all gave me the property sales price and information about the deed, actual county assessments, and the actual location of the file. I used pandas to do a large chunk of the data cleaning and making sure columns were correct or there were no inconsistencies in the data. I used the strap function to bring the datasets together so I didn't have any duplicates or other inconsistencies in my data. For my first analysis I got the number of sales, average price, and median sales price for the year. I grouped these transactions by city in the respective county.

##Findings
I looked at the years 2019,2020, and 2026. I wanted to see pre pandemic, during pandemic, and post pandemic pricing to see if there could be anything interesting. I looked at the transaction volume and comparing median prices and comparing in Boulder, Longmont, and Lafayette. These findings really only gave me an understanding for property sales regardless of foreclosure status. After my analysis I found that the location does play a large role but I am still unable to differentiate between foreclosures and other regular property sales. This is where Professor Keegan's feedback comes into play. I now plan on using Zillow data to give me more insight as I know Zillow has filters for this kind of thing. I will be working on this over thanksgiving break.


