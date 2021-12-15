# Kickstarting with Excel

## Overview of Project
Throughout this paper, you will find a thorough and comprehensive analysis of the Kickstarter crowdfunding campaigns, with special focus on Theater and Plays, and their outcomes based on different factors.

### Purpose
The purpose of this analysis is to determine the outcomes of Kickstarter crowdfunding campaigns based on two key factors: the launch date of the campaign and the goal set for the campaign.This will contribute some insight on important factors to maximize the chances of success of the campaign.

## Analysis and Challenges
The analysis was performed using Excel workbook containing all the information on the different Kickstarter campaigns, organized by category, subcategory, outcomes, goals set and launch date.

### Analysis of Outcomes Based on Launch Date
In order to correlate outcomes based on the launch date of the campaign, all the theater campaigns were included, from 2009 to 2017, grouped by the month of the launch date. Then the outcomes were broken down by nominal category (successful, failed and canceled). A grand total of 1369 campaigns were included, with 839 successful campaigns, 493 failed and 37 canceled. A detailed description of each launch date can be found in the following chart.

![Theater_outcomes_vs_Launch](https://user-images.githubusercontent.com/95982833/146120922-a160736f-936a-4c77-9339-f32c49680b28.png)

### Analysis of Outcomes Based on Goals
This analysis included only the plays, as a subcategory of theater, and were grouped in an ordinal manner, based on the goal set for each campaign. Twelve groups were formed, starting with campaigns with a goal of less than $1,000.00 and with subsequent intervals in increments of $5,000.00. The number and percentage of succesful, failed and canceled projects was determined for each group, as it is detailed in the chart found below.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95982833/146121239-d24a7a4e-eb9c-4c09-b8d4-1d22a35dde30.png)

### Challenges and Difficulties Encountered

The dataset provided needed reformatting in order to be easily accesible and analyzed, and variable standarization was required. Also timestamps had to be converted in order to be read and charted.

## Results

Based on the analysis performed on outcomes vs. launch date, it can be concluded that, although there are theater campaigns launched throughout the whole year, there is a seasonal trend towards late spring and summer, being this the times of the year with the greater amount of campaigns. It must be taken into account that most of the countries included in the dataset are located in the northern hemisphere. 

There is a remarkable peak of succesful campaigns in May, being this the month with most succesful outcomes, 111, followed closely by June with 100 and July with 87. In the subsequent months there is a decline in succesful campaings towards the end of the year. In contrast, although during the same months of peak success in campaigns there is an increase in failed campaigns due to the increased number of project launches, the trend remains stable later in the year.

According to this analysis the most suitable time of the year to launch a campaign in order to achieve the goal set, between May and August.

When we focus specially on plays, and the goals are taken into account, there is some overlapping in the percetages of succesful and failed campaigns and the different goals set. Notably, there is a somewhat direct correlation between the goal set and the succesful campaigns and an indirect one between failed campaigns. However most of the campaign goals are set in the lower quartile, where there is no significant difference between the percentages of succes and failure, so there is not a normal distribution. 

In conclusion, regarding the goals, the amount set is not the most important factor, however it should be taken into consideration that not a lot of projects set a goal over $15,000.00.

Also, in the financial aspect of the project, lies the greatest limitation of the dataset, because goals are set in local currencies, so differences in exchange rates, inflation rates, and local economic factors of each country must be taken into account in order to determine an appropriate goal for each campaign.

An interesting analysis could be made regarding the number of backers pledging money to the campaign, and the average amount of money pledged, being these two parameters a surrogate marker for popularity, according to topic, category or country.

