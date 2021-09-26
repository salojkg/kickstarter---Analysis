# Kickstarting with Excel

## Overview of Project
The objective of this project is to analyze the following
- Theater Outcomes based on Launch Date
- Outcomes based on Goal Chart – “Plays”

The result will help to gain an insight on the Outcomes for Theater & Outcomes based of Goals for Plays for future fundraisers. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

### Method Used 
  **Pivot Tables** and **Pivot Charts analysis**

I used Pivot Tables with fields filtered against Parent Category (Theater) and Year from the Kickstarter table. The data further drill downed based on Months and filtered with Successful, failed, and Canceled outcomes (Sorted in Descending Order). Let’s analyze the Data using Line Graph

<img src="/resources/Theater_Outcomes_vs_Launch.png"/>


#### Observations

- In Theater Category 62 % outcomes are successful based on the Launch dates, while the failed campagains accounts only 36 %. 
- The ideal time for Theater Campaigns is from April – July , which accounts about 50% of the total Successful outcomes.
-  May is the month with most successful outcomes.

### Analysis of Outcomes Based on Goals
I filtered  the data from Kickstarter sheet for analysis of Outcomes based on Goals for “Plays”. Here I used COUNTIFS function to filter the data against the Goal amounts based on ranges. Also used SUM, PERCENTAGE and Line graphs for the analysis.Let’s analyze the Data using Line Graph

<img src="/resources/Outcomes_vs_Goals.png"/>

#### Observations

- The most success rate for Plays falls in Goal category < $15000.
- The “Plays” Failure rate is high for > $50000 goal 

### Challenges and Difficulties Encountered
The Data Set: The Population / target audience is not explicitly described & the Campaigns are not uniformly distributed in all country. Most of them concentrated only in GB & US.

## Results

#### Conclusions about the Outcomes based on Launch Date
- The most successful outcomes for Theater Launch Date are May
- The ideal time for Launching the Theater Campaigns is from April – July

#### What can you conclude about the Outcomes based on Goals?
- Most Successful Goals for Play Fundraisers between 1000 to 4999 
- The “Play” Category is widely accepted mode of fund raising since the number of canceled outcome is Zero.

#### Limitations of this dataset
- Theater Outcomes based on Launch Dates: The Population / target audience is not explicitly described & the Campaigns are not uniformly distributed in all country. Most of the concentrated only in GB & US.
- Outcomes based on Goals: The analysis not taken in consideration of the following – Country, Year/ month. This might help in finding the correlation/ acceptability of plays & Outcomes.

#### Possible tables and/or graphs -Recommendations
- Theater Outcomes based on Launch Dates: Include Country Filer to analyze the Outcomes based on Country.
- Outcomes based on Goals: Analyze using Pivot table by Filtering Country, Month & Category (Plays) against the Goals. The will help us in throwing light to the acceptability of the Goals (Amount) , The best time to launch  & the target audience (Country).
