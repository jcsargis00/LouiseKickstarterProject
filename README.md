# Analyzing Data to Predict Success or Failure of Kickstarter Fundraising Campaigns with a particular interest in Theater and Plays

## Overview of Project and Purpose for Data Analysis
Louise's play *Fever* Kickstarter fundraising campaign was close to successful, but not in the short amount of time she allowed.  The purpose of this analysis is to determine what variables were in common in successful, failed, live and cancelled campaigns.  The data set analyzed is comprised of Kickstarter data from 4100 campaigns launched between May 2009 and March 2017.  The purpose of the study is to investigate campaign outcomes based on launch date and funding goal amounts.

## Analysis and Challenges
Additional visualization of the data using summary tables, charts and graphs will allow Louise  to see the outcomes of all the categories.  Although looking at the theater data as a category is insightful, additional detailed data will make the analysis more thorough.  By creating pivot charts and pivot tables, bar charts and line graphs generated from the data, links and trends can be looked for. These types of graphic visualizations make it easier to spot a trend than in a table (particularly if the table is large).   With this dataset, I was able to look at campaigns in the US (3038) or in Great Britain (604), where theater campaigns are most successful, since these are the two geographic areas Louise is interested in launching her play.  The length of campaigns, the time of year of the campaign launch, as well as, the goal funding amounts versus success or failure are also of interest.  Finally, I applied a filter on the data to hone in on theater and plays campaigns specifically.
### Analysis of Outcomes Based on Launch Date
Looking at the chart below, one can see that campaigns launched in May and June had the highes number of successful campaigns for theatre.  June, July and October had the highest number of failed campaigns.  From looking at these trends together, I would recommend Louise launch her fundraising campaign in May.
![Theater Outcomes Based on Launch Date](https://github.com/jcsargis00/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
Goals less than $1000 were 76% successful.  Goals around $45000 - $49999 was 100% unsuccessful. Goals around $10000 - $14999 were 54% successful and 46% failed.  At $20000 45% were successful, 55% failed.  By keeping the goal <$20000, the percentage of successful campaigns was above 50%.  If the campaign goal was below $5000 the success rate was %73.  I would recommend the campaign goal be less than $20000. By filtering the data further to include only plays, success was found with 238 out of 314 campaigns.
![Analysis of Outcomes Based on Goals](https://github.com/jcsargis00/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
Some of the challenges included getting the axis in several pivot charts to display properly, getting the correct variables into the correct categories for the pivot tables.  Additional, converting dates and then determining how much time elapsed between campaigns was a bit of a challenge.
## Results

- Conclusions you can draw about the Outcomes based on Launch Date
* May had the most successful campaigns (234 successful), with June a close 2nd (211 successful).
* Failed campaigns happened year round, with January, June, July, and October, had the highest number of failed campaigns, with 149, 147, 150 and 149  failed campaigns respectively.
* May is the best month  to launch with a high number of successful campaigna AND a relatively lower number of failed campaigns (126).  June had a high number of failure campaigns (147) along with the high number of successful campaigns (147).

- Conclusions about the Outcomes based on Goals
Campaigns under $5000 have the highes rate of success (73.4%). Campaigns between  more than $20000 and $25000 have a less than 45%.  There were 9 expensive campaigns with goals between $35000 and 545000 with a 67% success rate.  Campaigns over $50000 had a success rate of 13%, with 14 out of 16 campaigns failing.

## Summary of Limitations of the Dataset
Rather than call it a limitation, I would request desirable additional data if it could be found.  For example: 
* The most recent data is from 2017.  It would be a good idea to find more current data to see if trends are the same now
* Genre of plays, to look for trends of success or failure
* Demographic data (age, sex, income, etc.) of people attending plays and also backers, to look for trends
* Star power (famous actors), budget for each production, does this effect goal amounts and ability to attract backers, is this why a few expensive campaigns were successful?
* City location in addition to Country



## Possible tables and/or graphs to create and analyze
Campaigns duration varied greatly, from 1 day to 90.  Analysis of campaign length versus success/failure/live/cancelled 
Different charts to show Outcomes based on Goals, such as a stacked column
