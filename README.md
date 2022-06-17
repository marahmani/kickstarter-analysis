# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

# Kickstarting with Excel
Lousie wants to have more clarification about the campaigns she is working with and needs help with some analysis. We used Excel to help Louise with the these analysis.

## Overview of Project
By looking at the data initially we saw a huge dataset (a lot of rows are present in her dataset) and that by doing some simple calculations we may help her to be ready for her next campaign.

### Purpose

the Ourpose of this project is to help Louise get a better understanding about her dataand can decide to act on it better next time to get better result. also, to see which campain is better to incest time and money to get the most profit.

## Analysis and Challenges

Some of the analysis can easily get done by simple filtering to see for example how much money was spent for a single play. This estimation can be done rather quickly.
Using Excel, we started by creating a new column to determine how much of the campaign goal was met by calculating the percentage funded as =ROUND(E2/D2*100,0). 
Also, we calculated the Average Donation to find out how much money did people have pledged in general.
We used pivot table to show data into a summary that delivers information to have more visibility.
We have found that while there are only a total of 604 Kickstarter campaigns for plays in Great Britain, the "theater" category is the most successful.


### Analysis of Outcomes Based on Launch Date

We also helped Louise to see if the length of the campaign has anything to do with the success. Using a line chart helped us show the results more clearly to her. May was showing the most successful Kickstarter campaign launched month. So she can plan to take appropriate actions in this regards. Also she can see that in the months January, June , July and October the campaign was mostly failed.

![image](https://user-images.githubusercontent.com/49285767/174398073-63e79369-ba05-42d8-96b4-e202a13f73ae.png)

Again, by filtering the chart to the Theater, we can see that this is where it has the most success of all.

![image](https://user-images.githubusercontent.com/49285767/174398274-3472e0b9-06fa-4d76-8774-c5a9af0f5bfc.png)


### Analysis of Outcomes Based on Goals

We used ecxel to visualize the relationship between the goal-amount ranges based on the percentage of successful, failed, or canceled projects.

![image](https://user-images.githubusercontent.com/49285767/174407842-c780c09e-65e9-4bb0-aaf7-f8a961c08486.png)


### Challenges and Difficulties Encountered

We noticed some error in some cells and did debugging, found out that in some origin rows there were no numbers to divide it to, so we used IFERROR formula to fix this issue and replace the error with zero since we were dealing with numbers. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May was showing the most successful Kickstarter campaign launched month. So she can plan to take appropriate actions in this regards. Also she can see that in the months January, June , July and October the campaign was mostly failed.


- What can you conclude about the Outcomes based on Goals?

In the Outcome based on Goal analysis we can coclude that, whenever the the Goal was set less than 25000 or between the 35000 and 45000 , it was most successful. and it failed comepletely when it was set more than 45000.

- What are some limitations of this dataset?

When we identify the outlier, we can’t change or remove them since it will change our story. If we find out that the outliers are entered by mistake or typo, we want to fix it, If that is not possible, we would have to put out the data point. 

- What are some other possible tables and/or graphs that we could create?

category and subcategory to find out the best outcome based on the category.

