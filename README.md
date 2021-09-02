# Kickstarting with Excel

## Overview of Project

### Purpose
In this project, I used Excel to analyze a dataset consisting of crowdfunding projects to look for hidden trends. The client is an up and coming playright named Louise. She wants to start a crowdfunding campaign to fund her new play, Fever. Her initial estimate of her budget is over $10,000. 

Analysing and presenting the data from the crowdfunding website will help Luoise gain a greater understanding of how other campaigns in the same category were successful from start to finish. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A formula was used to convert the dates columns from Unix timestamps into a readable format. Another formula was then used to extract the year from the dates the campaigns were created in a new column titled **Year**. A pivot table was then created to analyze the data in the worksheet. Filters were added for two columns from the table, **Parent Category** and **Years**. The rows for the table utilized the **Date Created Conversion** column and are grouped to display by month. The values in the table are a count of the **Outcomes** column. **Outcomes** was also used for the columns in the table and are sorted in descending order. A line chart was then created, displayed below, to visualize the relationship between outcomes and launch month.

![Theatre Outcomes Based on Launch Date](../blob/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
A formula was used to collect the outcome and goal data from the Kickstarter data. A new sheet was created and populated with data for goal amounts, numbers of outcomes including a total, and percentages of outcomes. A line chart was then created to visualize a comparison of the outcomes.

![Outcomes Based on Goals](../blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
There were a few challenges encountered that were overcome using the resources available in the Excel software. The dates in the data needed to be converted so that they were readable. There was also a need to seperate the categories from the subcatagories.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The highest numbers of successful Theatre campaigns occured during the summer months of May, June, and July. This indicates that Louise will have the best odds of success for her play if she aims for a launch date within one of those months. Preference should be in May, which had the highest count of successful campaigns in the Theatre category.

The lowest number of successful campaigns was during the month of Decemeber. The number of failed campaigns for that month was almost equal. This indicates that launching a Theatre campaign during that month only has a slighlty better than 50% chance of being successful.

- What can you conclude about the Outcomes based on Goals?

The percantage successful was highest with the campaigns of a goal less than $20,000. There was one outlier over $40,000. The higher percantage of fails were with goals greater than $20,000. This indicates that Louise has the greater odds of success with a goal of $20,000 or less.

There were no canceled campaigns in the Plays subcategory.

- What are some limitations of this dataset?

This dataset could possibly benefit from more demographic information about the plays and where the backers donating were located.

- What are some other possible tables and/or graphs that we could create?

A table and graph could be created to show data on the number of backers that supported the campaigns.
