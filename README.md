# Kickstarter_analysis
Performing analysis on Kickstarter data
# Overview: 
This project examines different Kickstarter campaigns and how they performed concerning their launch dates and funding goals. 
## Analysis and Challenges: 
###### Analysis of Outcomes Based on Launch Date:
Starting from the Outcomes Based on Launch Date, I first created a pivot table based on the `Parent Category` and `Year` columns. After that, by filtered the `Parent Category` by `Theater` within the pivot table, we now can analyze the theater category. Finally, I created a dotted line chart from the pivot table in order to complete the  visualize the relationship between outcomes and launch month.
The line chart shows the number of successful, failed, or canceled projects by month. From here, we can see how each month impacted the fundraising campaign outcome with the line chart visualization:
###### Pivot Chart
![image_name](path/to/Theater_Outcomes_vs_Launch.png)
###### Challenges and Difficulties Encountered
Excel is a tool that can be used across all Organizations areas, some of the tools are quite easy to follow, but for anyone that is new to Excel, it can be a little bit overwhelming determining the correct formular and their placement to get the results that you need. Also, it is quite confusing to figured out the budget range by using `COUNTIFS()` formular when from the second database that is provided. 
## Result:
###### Two conclusions about the Theater Outcomes by Launch Date:
1. May is the month with the most successful Kickstarter campaign. 
2. Campaigns are  had roughly the same number of failed campaigns launched in the Winter time and early Spring. (i.e November-March).
As we can see in the line chart, the more funding goal amount increases, the higher chance that the rate of successful projects will decrease. Therefore, Campaigns are more successful when reasonable goals are set.
###### Limitations of this dataset:
1. The data does not have marketing metrics, this project may have had a larger marketing budget to increase the amount of sign-up backers.
2. Identify the backers by gender. This may help to determine target audience, gender, or age.
3. The date does not have more detailed information about donation statistics. We are not allowed to access to the individual person's data that donated.
A possible graph that we could create could be a line chart on the project's outcome based on average donation.
