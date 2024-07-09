# excel-challenge
Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

To receive funding, the project must meet or exceed an initial goal, so many organisations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. For this week's Challenge, you will organise and analyse a database of 1,000 sample projects to uncover any hidden trends.
Instructions
Using the Excel workbook in your .zip file, modify and analyse the sample-project data and try to uncover market trends.

Use conditional formatting to fill each cell in the outcome column with a different colour, depending on whether the associated campaign was successful, failed, cancelled, or is currently live.

Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
Use conditional formatting to fill each cell in the Percent Funded column according to a three-colour scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

Create a new sheet with a pivot table that analyses your initial worksheet to count how many campaigns were successful, failed, cancelled, or are currently live per category.
Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

Create a new sheet with a pivot table that analyses your initial sheet to count how many campaigns were successful, failed, or cancelled, or are currently live per sub-category.

Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formulaLinks to an external site. that can be used to convert these timestamps to a normal date.

Create a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.

Create a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.

Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

Now, create a pivot-chart line graph that visualises this new table.
•	Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
o	Increasing crowdfunding campaigns tend to be successful rather than unsuccessful.
o	Crowdfunding for theater projects, specifically plays, tend to be popular and more successful. However, if you calculate the percentage of total campaigns and failure ratio, it also has the highest percentage of failures.
o	About 43% cannot reach to the goal amount for crowdfunding, and about 57% meet their goal of crowdfunding.
o	Those who want to raise $50,000 or more had least ratio of meeting the goal..
•	What are some limitations of this dataset?
o	Some limitations on this data are failing to explain why some crowdfunding campaigns cancelled or failed.
o	There could be more specific categories compared to the sub-categories listed. For instance, food trucks is supposed to be a sub-category. But what types of food trucks tend to be successful or failed? Does this result in the failure to raise money?
•	What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
o	Create a pivot table to reflect by category, and did the time they launched to the deadline, bring in crowdfunding that was more successful or not? Did projects with a short deadline have more chance to fail? 
o	What was the average time from launch to deadline by category? This contributes to  be useful for people who aim to utilize crowdfund to reach certain goals. 
o	What was the average financial goal, per category and sub-category, to get those thinking about starting a crowdfunding campaign ready?


