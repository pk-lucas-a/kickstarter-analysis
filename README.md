# An Analysis of Kickstarter Campaigns
Analysis of Kickstarter data to uncover trends

## Overview of Project
This analysis included outcomes based on month of crowdfunding launch date and outcomes based on goal amounts. 

### Purpose
A playwright plans to use crowdfunding for a play in the US. A 2014-2016 Kickstarter dataset with outcomes was analyzed to uncover trends and insights to consider when setting up a new campaign. 

## Analysis and Challenges   "Explain how you performed your analysis"

### Analysis of Outcomes Based on Launch Date
A line chart was created to show the relationships between the outcomes and the launch month. First, a variable for year was added to include in a pivot table with parent crowdfunding category data. The pivot table includes columns for the outcomes "canceled," "failed," and "successful," as well as a total campaigns. The rows included each month of the year. 


### Analysis of Outcomes Based on Goals
A line chart was created to show the relationship between currency goal amounts and the percentages of different outcomes. First, the COUNTIFS function was used to get counts of successful, failed, canceled, and total projects for each of 12 binned goal amounts. These were converted to percentages and graphed. 
(Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Excel froze several times, so I made sure to save frequently. I closed Excel while still working with the date columns and found that my date formatting was lost before I made the new date columns, so that should be completed before closing Excel. The number of sheets created resulted in a lot of confusion and retracing steps when writing the report. With 14 initial sheets I should have written the report as I went. If we were to compare goal or pledged amounts between different countries, we would need to convert the currencies first.

## Results

### Conclusions about Outcomes based on Launch Date
More than half of theater campaigns were successful. Theater successes spiked for campaigns that began in May, and were least common for campaigns that began in December. Campaigns that began in the summer were both more common and more successful than campaigns that began in the winter. 

### Conclusions about Outcomes based on Goals
There is a negative overall trend between percent successful and goal amount. However, the number of Kickstarters with goals over $2,5000 were relatively rare compared to below $25,000, so the data is less significant beyond that point. This probably explains the jump in successful plays relative to failed plays between $35,000 and $44,999. We would therefore conclude that there is a positive overall trend between percentage failed and goal amount that begins around 20% failed for less than $1,000 and increases to about 80% failed for goals over $50,000. Chances are about 50/50 for success/failure at the goal amount of 15,000-19,999, so exceeding this threshold makes failure more likely than success.

### Limitations of this dataset
This dataset did not include any cancelled plays, and very few plays with goals over $25,000, so our insights are less confident in those areas. We would prefer a larger sample of US plays so we could look specifically at that market. 

### Potential further analysis 
We could graph percent of plays by outcome for each starting month or week of the year. 
We could make box plots of amounts pledged, or of US Musicals by outcome to compare to our US Plays boxplot. 
We could see if being a staff pick or spotlight is related to amounts pledged with a table comparing average amounts pledged for staff picks and non staff picks, and spotlights and non spotlights for plays in the US. 
