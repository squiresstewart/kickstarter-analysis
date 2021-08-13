# Kickstarting with Excel

## Overview of Project

This project is an analysis of a variety of startup global entertainment mediums and venues, their financial statistics,
as well as startup outcomes. With this project one can query specific key factors and show how those factors may affect the successes or failures of those startups through trends.

### Purpose

This project is to show methods used to import and sort data, filtering by the type of data one might want, using pivot tables to see a graphical representation of the desired data as well as exporting those images for other uses, and populating new tables in new sheets using Excel formulas for deeper analysis.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To perform the analysis of outcomes based on launch date, I filtered the Kickstarter worksheet to grab the data for the selected criteria being theater. I then selected all the data that remained in the worksheet after filtering and created a pivot table. I was able to filter my pivot table for even more specific criteria to create an adequate chart sorted by failed, successful, and cancelled events in the theater subcategory, organized by the months of the year.



### Analysis of Outcomes Based on Goals

To perform the analysis of outcomes based on goals, I created a new worksheet with column headers of the total of successful, failed, and cancelled shows as well as their percentage of the whole. These numbers were then sorted by their goal amounts as indicated by the row headers. Data in the table is populated using the Excel function COUNTIFS() referencing specific columns and cells in other worksheets in the project. Some of the formulas required equations and conditionals based upon their respective locations in the new table. If those cells queried met those conditions, the COUNTIFS() function adds to the count and placed that value in the cells in my new table.

### Challenges and Difficulties Encountered

I originally started to make this table using filters similar to the method noted in Outcomes Based on Launch Date. My table and chart were not appearing as they should according to lesson. I knew there was a way to make my excel formulas do the filtering for me instead, but I didn't know how just yet. I used the "Insert Function" tool to explored other typed of functions. I was able to confirm by suspicion that the formula can do the filtering for me by listing all of my conditionals in the COUNTIFS() function.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

One can conclude that theater outcomes are more successful when launch dates are scheduled in the spring and summer.

One can also conclude that most seasonal Halloween shows are never cancelled.

- What can you conclude about the Outcomes based on Goals?

One can conclude that shows with a lower goal have a higher probability of success.

One can also conclude that when it comes to plays, no matter what the goal is, the show must go on as there are none cancelled.

- What are some limitations of this dataset?

One limitation of the data set is that there is no accounting for revenues gained during shows and whether those revenues pushed failed goals into successful status.

- What are some other possible tables and/or graphs that we could create?

A vertical bar graph could be generated indicating which subcategories are most popular based upon successful goal outcomes and the number of backers.
