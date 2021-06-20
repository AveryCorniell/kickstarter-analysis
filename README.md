# Kickstarting with Excel  

## Overview of Project  

### Purpose  

The purpose of this kickstarter analysis is to provide my client (Louise) with an analysis of how well she fared with her crowdfunding goals in comparison to other Theater campaigns.  
The comparisons were made in relation to the launch dates and funding goals.  

## Analysis and Challenges  

Beginning with 4114 rows of a tabular data set, some data had to be reformatted or seperated in order to retrieve the desired information.  
For example, the launch and deadline dates were given in Unix timestap and had to be converted to a human date for usefulness.  
I relied on two resources to accurately complete this task:
- <https://stackoverflow.com/questions/46130132/converting-unix-time-into-date-time-via-excel>  
- <https://www.epochconverter.com/>  
Once reformatted, I used the Launch date as one of the basis for analyzing the outcomes.  
Also, since Louise is interested in theater outcomes, most importantly musicals, I had to seperate the category column into two columns (parent category and subcategory)  
![New Colums Created](D:\Vanderbilt-DataAnalyticsBC\Module1\Crowdfunding Analysis\NewColumnsCreated.png)  
![Parent Statistics](D:\Vanderbilt-DataAnalyticsBC\Module1\Crowdfunding Analysis\ParentStatistics.png)  
![Subcategory Statistics](D:\Vanderbilt-DataAnalyticsBC\Module1\Crowdfunding Analysis\SubcategoryStatistics.png)  

### Analysis of Outcomes Based on Launch Date  
![Outcomes Based on Launch Date](D:\Vanderbilt-DataAnalyticsBC\Module1\Crowdfunding Analysis\Resources\Theater_Outcomes_vs_Launch.png)  

### Analysis of Outcomes Based on Goals  
![Outcomes Based on Goals](D:\Vanderbilt-DataAnalyticsBC\Module1\Crowdfunding Analysis\Resources\Outcome_vs_Goals.png)  

## Results

- Based on the analysis of Outcomes Based on Launch Date I can conclude that:  
	- Most successful campaigns were launched in May.    
	- There is a 50/50 chance of success or failure for campaigns launched in December.  

- Based on the analysis of Outcomes Based on Goals I can conclude that:  
	- 76% of campaigns with a goal of $1000 or less were successful  
	- In order to have and at least 50% chance of a successful campaign, goals should not be higher than $19,999.  

- Some limitations of this dataset were:  
	- Of the 4114 records, only 140 were musicals, and of that 140 the dates "campaign was created" ranged from the years 2014 - 2017 with most falling in either 2014 or 2015.  
	- There is no data on what each backer contributed individually; so there is no way of determining an accurate mean backer pledge.  

- Some other possible tables and/or graphs that could have been created include:  
	- Average number of backers for successful campaigns.  
	- How long it took for successful campaigns to reach their goals by calculating the difference between the date campaign was created and the date campaign ended.  

