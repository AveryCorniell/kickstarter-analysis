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
![NewColumnsCreated](https://user-images.githubusercontent.com/83401820/122660483-8f2e6e00-d147-11eb-80ce-fd8117feb23a.png)  
![ParentStatistics](https://user-images.githubusercontent.com/83401820/122660484-8f2e6e00-d147-11eb-95e3-ba0d7914846b.png)   
![SubcategoryStatistics](https://user-images.githubusercontent.com/83401820/122660482-8e95d780-d147-11eb-8da5-70bd246fa452.png)  

### Analysis of Outcomes Based on Launch Date  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/83401820/122660542-f1876e80-d147-11eb-8d6d-4c689876ea1e.png)    

### Analysis of Outcomes Based on Goals  
![Outcome_vs_Goals](https://user-images.githubusercontent.com/83401820/122660543-f2200500-d147-11eb-8040-0a46e588e6fc.png)    

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

