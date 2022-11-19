# Kickstarting with Excel

## Overview of Project
This project demonstrates the capability of Excel to analyze data and uncover trends relating to Kickstarter campaign data.
### Purpose
The purpose of this project is to assist a client (Louise) in deciding if or when to start a crowdfunding Kickstarter campaign for her play Fever.
## Analysis and Challenges
To create a palatable view of the project it was broken down into two main deliverables, outcomes based on launch date and outcomes based on goals.
### Analysis of Outcomes Based on Launch Date
The purpose of this analysis was to look at outcomes from the category of "theater" campaigns which was then further broken down into a subcategory of "plays", these were then filtered by year and month that the campaigns began. To achieve this, I created a pivot table that looked at "theater" category, the start month/year of every campaign, and the outcomes of the campaigns. The pivot table was filtered for "parent category" and "years", launch date for rows, and "outcomes" for values and columns. Once the pivot table was complete, it was used to create a line chart to visually show the outcomes based on which month the campaign began.
![Theater_outcomes_vs_launch.png](resources/Theater_outcomes_vs_launch.png)

### Analysis of Outcomes Based on Goals
To analyze the Outcomes of "Plays" campaigns based on goals several things were done. First I made a table to sort the goals into three categorys, successful, failed , and canceled. Then the COUNTIFS function was used to fill the table based on each dollar range. Additionally the SUM function was used to obtain a total number of campaigns based on dollar range. Next percentages were calculated using the existing table data. Finally using the table as a source, I made a line chart to visualize the table data.
![Outcomes_vs_goals.png](resources/Outcomes_vs_goals.png)
### Challenges and Difficulties Encountered
While creating this analysis I ran into a couple difficulties. Firstly while creating the pivot table for Outcomes Based on Launch Date I had issue filtering the pivot table by months rather then years. I was able to overcome this by googling and some trial and error. Additonally I ran into an issue when trying to create the data table for outcomes based on goals, my issue was with the COUNTIFS function. While attempting to add a range for the data based on specific dollar amounts I could not figure out how to add a range of numbers. I managed to overcome this through watching a video that explained how the function works. Finally getting the function to work the way I wanted was fulfilling. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The largest conclusion drawn from this analysis was that May and June are the best months to start a campaign. May and June both had very high success rates with low failure rates. Another conclusion is that October, November, and December were the worst months to start a campaign. October had an abnormal failure rate, November had the second lowest success rate. December had the lowest success rate which almost equaled its failure rate.
- What can you conclude about the Outcomes based on Goals?

The main conclusion from outcomes based on goals would be that campaigns with goals under 5000 are going to be the most successful. Campaigns under 5000 had an over 70% of success which beat out the higher $ goal campaigns which only had a 50% chance of success. 

- What are some limitations of this dataset?

When breaking down this data set into "plays" category it produced a small subset of data. When looking at the higher $ goal campaigns it was clear there was a lack of data which can cause the data to skew. In the 45000 to 49999 range there was only a single campaign, with such limited data it is difficult to see if the $ range was the reason for success or failure.
- What are some other possible tables and/or graphs that we could create?

We looked at outcomes based on launch date and goals, instead we could look at average donation or the deadline for the campaign. We could create line charts and pivot tables just like we did for goals and launch date. Additionally we could look at other categorys of campaigns like musicals to see how they compare to plays.
