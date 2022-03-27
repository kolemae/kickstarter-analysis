# Kickstarter Campaign Analysis
An analysis of Kickstarter data focused on play funding. I learned and implemented Excel analysis; PivotTables, PivotCharts, and common analysis formulas, for the first week of a 6 month Data Analytics Bootcamp.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Analysis and Challenges](#analysis-and-challenges)
* [Parent Category Outcomes](#parent-category-outcomes)
* [Subcategory Outcomes](#subcategory-outcomes)
* [Outcomes Based on Launch Date](#outcomes-based-on-launch-date)
* [Theater Outcomes Based on Launch Date](#theater-outcomes-based-on-launch-date)
* [Outcomes Based on Goals](#outcomes-based-on-goals)
* [Results](#results)

## Overview of Project
This analysis is for Louise, who wanted to launch a Kickstarter campaign to fund a play in the US. The play was estimated to cost $12,000, with a goal of $10,000 for the Kickstarter. She wanted this analysis to make a more informed decision about launching a Kickstarter for her play. Following the launch of her Kickstarter, Louise wanted to compare the outcomes of other campaigns based on launch date and funding goals.

## Analysis and Challenges
<!-- Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered. -->

For my analysis I used Conditional Formatting, PivotTables, PivotCharts, IF/IFS, COUNTIF/COUNTIFS, VLOOKUP, AVERAGE, MEDIAN, STDEV.P, QUARTILE.EXC, and a date conversion formula to organize and clean the data.
- For the date conversion formula use `=(((J2/60)/60)/24)+DATE(1970,1,1)`

Some challenges I faced were
- Limited information available in the data
  - There aren't many Kickstarters for plays similar to the client's goals
  - Plays and other subcategories don't have genres attached
  - No mention of what backer benefits the Kickstarters offered (if any)
  - Location within countries isn't accounted for
- Same colorcoding throughout visuals

Using resources available within the module and using Google I was able to fix any errors. In the future I would color outcomes like 'successful' and 'failed' so they're more clearly differentiated.

### Parent Category Outcomes
Theater Kickstarters have the highest count for all categories, with a success rate of 60%.

![Parent Category Outcomes](https://github.com/kolemae/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes.png)

US theater Kickstarters have a similar success rate of 58%.

<img src="https://github.com/kolemae/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes%20-%20US%20Theater.png" width="481" height="288" />

### Subcategory Outcomes
Kickstarters for plays have the highest count for all theater subcategories and the highest theater subcategory success rate at 65%.

![Subcategory Outcomes](https://github.com/kolemae/kickstarter-analysis/blob/main/Subcategory%20Outcomes.png)

Within the US, Kickstarters for plays have a success rate of 54%.

<img src="https://github.com/kolemae/kickstarter-analysis/blob/main/Subcategory%20Outcomes%20-%20US%20Plays.png" width="481" height="288" />

### Outcomes Based on Launch Date

Kickstarters launched between February to May saw higher rates of success compared to failure. 

![Outcomes Based on Launch Date](https://github.com/kolemae/kickstarter-analysis/blob/main/Launch%20Date%20Outcomes.png)

US Kickstarters for plays have slightly different launch date outcomes, with higher success to failure rates between May and August.

<img src="https://github.com/kolemae/kickstarter-analysis/blob/main/Launch%20Date%20Outcomes%20-%20US%20Plays.png" width="481" height="288" />

### Theater Outcomes Based on Launch Date

Theater Outcomes Based on Launch Date indicates that May has the highest rate of success for launched Kickstarters. October through December have similar numbers of Successful and Failed Kickstarters and wouldn't be a good time to launch.

### Outcomes Based on Goals

Outcomes Based on Goal shows that plays with goals below $5,000 have a better success to failure percentage gap overall.

## Results

Based on the data I'd recommend that you launch your Kickstarter campaign between May and August. You could also consider lowering the Kickstarter goal for greater success. Most play Kickstarters have a higher chance of success when the goal is below $10,000. However, there are 62 successful Kickstarter campaigns for US Plays with goals of $10,000 or higher. Out of these, 24 had goals equal to $10,000 with the highest count of success launched in August. Other tables or graphs that would benefit you are US Play specific ones, Kickstarter plays with similar goals of $10,000, and Outcomes Based on Length of Kickstarter Run. 
