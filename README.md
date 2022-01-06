# Analyzing Data to Predict Success or Failure of Kickstarter Fundraising Campaigns with a particular interest in Theater and Plays
Data driven analysis on Kickstarter campaign datasets to look for specific variables that make campaigns successful.
## Overview of Project and Purpose for Data Analysis
Louise's play *Fever's* Kickstarter fundraising campaign was close to successful, but not in the short amount of time she allowed.  Her funding goal is $10000, based on her budget. The purpose of this analysis is to determine what variables were in common in successful, failed, live and cancelled campaigns.  The data set analyzed is comprised of Kickstarter data from 4100 campaigns launched between May 2009 and March 2017.  This study specifically investigated campaign outcomes based on launch date and funding goal amounts.  The goal is to provide Louise with a better understanding of factors leading to a successful campaign.

## Analysis and Challenges
The dataset required sorting and conditional formatting to determine results of campaigns in the Theater category.  Additional visualization of the data using summary tables, charts and graphs was performed to see the outcomes of all the categories.  Although looking at the theater data as a category is insightful, additional detailed data made the analysis more thorough.  By creating pivot charts and pivot tables, bar charts and line graphs generated from the data, links and trends can be looked for. These types of graphic visualizations make it easier to spot a trend than in a table (particularly if the table is large).   Included in this dataset are campaigns in the US (3038) and Great Britain (604), where theater campaigns are most successful, since these are the two geographic areas Louise is interested in launching her play.  The length of campaigns, the time of year of the campaign launch, as well as, the goal funding amounts versus success or failure are also of interest.  Finally, a filter was applied to the data to hone in on data pertaining to theater and plays campaigns specifically.
### Analysis of Outcomes Based on Launch Date
Looking at the chart below, one can see that campaigns launched in May and June had the highest number of successful campaigns for theatre.  May, June, July, August and October had a similar and high number of failed campaigns, but the worst month was December, with a high rate of failed campaigns and a low rate of successful campaigns.  From looking at these trends together, and seeing the biggest gap between successful and failed campaigns, the best month for Louise to launch her fundraising campaign is in May.
![Theater Outcomes Based on Launch Date](https://github.com/jcsargis00/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
Funding goals less than $1000 were 76% successful.  Goals from $45000 - $49999 were 100% unsuccessful. Goals from $10000 - $14999 were 54% successful.  At $20000, 45% were successful.  By keeping the goal <$20000, the percentage of successful campaigns was above 50%.  If the campaign goal was below $5000 the success rate was %73.  A recommendation based on the findings in the dataset, would be to set the campaign goal to be less than $20000. By filtering the data further to include only plays, success was found with 238 out of 314 campaigns.
![Analysis of Outcomes Based on Goals](https://github.com/jcsargis00/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
Some of the challenges included organizing and filtering the data, getting the axis in several pivot charts to display properly, and getting the correct variables into the correct categories for the pivot tables.  With pivot tables, it is very easy to create a strange chart with no meaning if the correct variables and filters are not selected.  Additionally, converting dates and then determining how much time elapsed between campaigns was a bit of a challenge.
## Results

### Conclusions Drawn from Outcomes based on Launch Date
* Timing of the start of the campaign was an important factor.
* May had the most successful campaigns (234 successful), with June a close 2nd (211 successful).
* Failed campaigns happened year round, with May, June, July and October, having the highest number of failed campaigns, with 149, 147, 150 and 149  failed campaigns respectively.
* May is the best month  to launch with a high number of successful campaigna AND a relatively lower number of failed campaigns (126).  June had a high number of failure campaigns (147) along with the high number of successful campaigns (147).
* December had a medium number of failures together with a low number of successes, making it a riskier choice as a month to start a campaign.

###  Conclusions about the Outcomes based on Goals
* Campaigns under $5000 have the highest rate of success (73.4%). 
* Campaigns over $20000 have less than a 50% chance of success.  Specifically, campaigns between  $20000 and $25000 were 45% successful.  
* Expensive campaigns can be successful.  There were 9 expensive campaigns with goals between $35000 and 45000 with a 67% success rate.  Campaigns over $50000 had a success rate of 13%, with 14 out of 16 campaigns failing.

## Summary of Limitations of the Dataset
Rather than call it a limitation, a request for additional data if it could be found could prove informative.  
For example: 
* The most recent data is from 2017.  It would be of interest to find more current data, to see if trends are the same now. A lot has happened since 2017, like a pandemic.
* Genre and themes of plays, to look for trends of success or failure
* Demographic data (age, sex, income, etc.) of people attending plays and also demographics of backers, to look for trends
* Star power (famous actors), budget for each production, does this effect goal amounts and ability to attract backers, is this why a few expensive campaigns were successful?
* City location in addition to Country, would this change trends?

## Possible tables and/or graphs to create and analyze
- Campaigns duration varied greatly, from 1 day to 90.  Charts featuring analysis of campaign length versus success/failure/live/cancelled 
- Different types of charts to show Outcomes based on Goals, such as a stacked column
- Cluster charts to show more variables
