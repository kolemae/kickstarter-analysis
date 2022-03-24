# Kickstarter Campaign Analysis
An analysis of Kickstarter data focused on play funding. I learned and implemented Excel analysis; PivotTables, PivotCharts, and common analysis formulas, for the first week of a 6 month Data Analytics Bootcamp.

## Table of contents
* [Overview of Project](#overview-of-project)
* [Analysis and Challenges](#analysis-and-challenges)
* [Parent Category Outcomes](#parent-category-outcomes)
* [Subcategory Outcomes](#subcategory-outcomes)
* [Outcomes Based on Launch Date](#outcomes-based-on-launch-date)
* [Recommendations](#recommendations)
* [Results](#results)

## Overview of Project
This analysis is for Louise, who wanted to launch a Kickstarter campaign to fund a play in the US. The play was estimated to cost $12,000, with a goal of $10,000 for the Kickstarter. She wanted this analysis to make a more informed decision about launching a Kickstarter for her play. Following the launch of her Kickstarter, Louise wanted to compare the outcomes of other campaigns based on launch date and funding goals.

## Analysis and Challenges
<!-- Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered. -->



While I *was* familiar with basic Excel formulas like SUM, AVERAGE, nested formulas, and making charts, I made a few errors that took a while to weed out. VLOOKUP, IF/IFS, COUNTIF/COUNTIFS, and using '$' to keep cell values from changing were all new to me. I had never made such large and relatively advanced nested functions before. Several times I had to backtrack because I was missing quotations, whole sections of criteria in my formulas, or something else that threw everything off. Through trial and error, using the resources and hints provided in the module, **LOTS** of Googling, and in one case completely restarting a worksheet, I was able to fix my errors and also saved the 'fixed' and 'error' versions separately so I could use it as a reference if I hit a similar snag moving forward. A smaller challenge was realizing that colors don't always stay the same when making different charts if a legend value is missing from that chart. I have become *very* good at changing the legend series colors so that when looking at all the charts you don't get thrown off by different colors despite looking at the same value from previous charts. In the future I would color outcomes like 'successful' and 'failed' so they're more clearly differentiated in my images.

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

### Recommendations

Based on the data I'd recommend that you launch your Kickstarter campaign between May and August. You could also consider lowering the Kickstarter goal for greater success. Most play Kickstarters have a higher chance of success when the goal is below $10,000. However, there are 62 successful Kickstarter campaigns for US Plays with goals of $10,000 or higher. Out of these, 24 had goals equal to $10,000 with the highest count of success launched in August.

## Results
<!-- What are two conclusions you can draw about the Theater Outcomes by Launch Date?
What can you conclude about the Outcomes based on Goals?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create? -->
