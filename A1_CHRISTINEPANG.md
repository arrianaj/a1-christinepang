CEE 224X | Released: 180925 | Due: 181002
Name: Christine Pang

#### Q1: What are the “Combined” fields referring to? How do you think this information may affect our analyses?

The "Combined" fields refer to whether or not the PG&E energy datasets met the Commission Decision aggregation requirements regarding the minimum number of Residential (100) and Non-Residential (15) customers and their respective contributions to total consumption. If the aggregation was not met, consumption data was combined with that from neighboring zip codes until the requirement was satisfied, indicated by "Y" in the cell. Combining data across different zip codes could cause our analyses on energy consumption in a region to be not representative of the actual consumption in the particular zip code listed.



#### Q2: Why are the “Average” fields likely not useful for our analyses?

The "Average" fields represent the average electricity or gas use per customer per zip code per month, and these numbers are not likely useful for our analyses because the number of customers across the 12 months and zipcodes varies. This means that it wouldn't be accurate to mathematically combine or add these average values together to obtain an annual average of energy consumption because the data were taken over different sized populations and could be referencing different customers. 



#### Q3: What type of calculations should "X" and "Y" be in the step above? Why?





#### Q4: What is the total KBTU combined electricity and gas consumption in PG&E territory in 2017? What is the average annual electricity consumption per customer, and average annual gas consumption per customer?

The PG&E data files double count the month of September (month 9) in the Q3 and Q4 reports, so I only used the September results from the Q3 report and deleted those from the Q4 report. After doing this, the total KBTU combined electricity and gas consumption in PG&E territory for the Residential Customer Class in 2017 is 2.7371E+11 kBTU. The average annual electricity consumption per customer is 21953 kBTU and the average annual gas consumption per customer is 43268 kBTU.



#### Q5: How would you explain the results of this chart to an average property owner in Northern California? What would be the value of conducting further "seasonal" analyses of energy use, compared to "year-long" analyses, and how would you define seasonal boundaries?

The chart results indicate that residents in Northern California use the most gas in the winter months (around November – April). This is due to colder weather causing residents to use their heaters more. The electricity usage is roughly constant throughout the year but slightly greater in the summer months of July and August. This is because while summer months are hotter than the rest of the year, northern California generally does not experience extremely hot temperatures, so people won’t use their air conditioners as much.
“Seasonal” analyses of energy use would be beneficial to better understand the fluctuations of energy use within a season or month(s) because we can see that it changes drastically throughout the year, so any action proposed to change energy use should depend on the season. Comparatively, a “year-long” analysis would only report energy consumed over the whole year and would not be able to differentiate between months of the year that contain the largest energy usage. 
For Northern California, I would define seasonal boundaries based on the amount gas and electicity used in a month along with its rate of change over the year. Winter is December - February, which has the highest gas usage. Spring is March – May (gas usage decreases), Summer is June – August (gas usage stabilizes, electricity usage increases), and Fall is September – November (gas usage increased, electricity usage decreases).




#### Q6: Explain your choice of formula for "avgkbtu".

I first calculated the total number of electricity and gas customers separately by averaging the number of customers listed over the 12 months for each zip code and then summed them over all zip codes. To account for some zip codes having just electricity customers, some having just gas customers, and some having both, I calculated "avgkbtu" differently for each. For zip codes with just electricity or gas customers, the average kBTU per customer was the total electricity or gas kBTU for the year divided by the total respective customers. For the combined (electricity & gas customers) case, the two opposite ends of the spectrum to consider were that all electricity and gas customers are independent of each other or that all gas customers are also electricity customers. For residential areas, I believe it's more likely that gas and electricity customers are overlapped so I calculated average kBTU as total electricity + gas kBTU divided by the larger of electricity or gas customers.



#### Q7 Paste a publicly viewable link to your Slides.

https://drive.google.com/open?id=1ImHp3HNFTN2WhCwSonvjgIqOxPKlhOsdFc8VFexiF6g



#### Q8 In what ways do the results in or in the vicinity of your chosen zip code validate or contradict your expectations?

It is interesting to see that Stanford's average kBTU consumption per customer is in the highest bracket whereas its total consumption is in the lowest bracket due to the zip code having fewer customers than the other zip codes near it. This agrees with my expectation that the average energy consumption per customer is high in Stanford because there are many students living close together (like in residence halls) that would constitute one "customer" by PG&E, but collectively they use a lot of electricity/gas.



#### Q9 Any other reactions to completing Pass One? What was especially challenging or surprising in the workflow? How might you expand on this analysis if you had more time?

The most challenging parts for me were getting used to all of the different analysis tools and software that I have never used before (I'm still even getting used to slack) and trying to not get overwhelmed by them. I was surprised by how helpful and useful pivot tables are even though it took a while to understand. This analysis could be expanded by looking into the seasonal variations of energy consumption to see if there see if different areas use more energy at different times of the year or if the annual spatial variation of energy use is representative of the whole year.



#### Q10 How would you compare the experienced or apparent work involved, as well as the usefulness of the outcome, of Pass One vs. Pass Two? How would you rate the difficulty of this assignment?

There was much more work involved in Pass One than Pass Two but that is because I didn't write my own script for the R or Python code. If I had, I think Pass Two would have been much more difficult for me since I don't have much experience in either and even encountered some problems when using the provided R code. In terms of the end product of both passes, the usefulness is about the same, but in terms of how much I learned, the first pass was more helpful in teaching me how to use ArcGIS and how to process data.



#### Q11 In total, how long did Assignment 1 take?

Part 1: Tech Setup: 150 minutes

Part 2: Pre-Assessment: 30 minutes

Part 3: Readings: 30 minutes

Part 4: Practice Data Dive: Pass 1: 480 minutes (but I am slow and had to redo things a few times)

Part 4: Practice Data Dive: Pass 2: 120 minutes
