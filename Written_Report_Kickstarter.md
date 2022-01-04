# Kickstarter with Excel

## Overview of Project
Plays' launch dates and funding goals will influence campaign outcomes. Louise wants to know about her play Fever in its close situation, in which how different campaigns fared concerning their launch dates and their funding goals. So she can change her strategies on campaigning based on the previous campaign outcomes, for example, change goals limits or launch dates, etc.
### Purpose
Based on Kickstarter's database, we will visualize the changes between the launch date and funding on teh goals.
## Analysis and Challenges
1. looked at the date and divided category and subcategories. calculated year for the launch date and deadline
2. I used calculation percentage using COUNTIFS for success/fail/canceled section was challenging since I needed to change every step. I used two ways to know whether I used it correctly. Pivot is faster and straightforward for me. 
3. I cannot figure out when I calculated the year by changing the launch date in the pivot table. I do not know how the years came out automatically in the pivot table fields. I still do not know that.
### Analysis of Outcomes Based on Launch Date
1. choose theater from parent category and all years as listed by month. From the figure (OutCome by launch date), we can see the patterns in which theaters are better in success compared to failed and canceled. 
2. within years, the outcomes of theater are different based on months. May is the best time, but December could be the worst time.
3. technology used: pivot table and pivot chart
### Analysis of Outcomes Based on Goals
1. there were apparent differences between lower goals on success and failed outcomes.
2. a higher percentage of failed and a lower percentage of success came from the higher goals. It could implicate that higher goals may not be very successful.
3. There are many lower goal-based projects and a few high goal-based projects in total.
### Challenges and Difficulties Encountered
1. background information was not very clear to me
2. pivot table took time to figure out.
## Results

- What are two conclusions you can draw about the Outcomes-based on Launch Date?
1. the total outcome of a successful theater launch date is higher than failed and concealed. There were fewer concealed in a theater compared to success and failed ones.
2. the launch date could influence the outcome of theater. It seems May is the best time, and December is teh worst time.
- What can you conclude about the Outcomes-based on Goals?
1. a low amount of goals had more successful targets than a high amount of goals.
2. the total number of projects based on the low goal amounts is more than the one in high goal amounts. There were apparent differences between successful and failed projects on the low goal amounts.
- What are some limitations of this dataset?
1. percentages cannot represent the changes of successful vs. failed projects.
2. Without statistical analysis, it is only teh descriptive level with rough predictions but cannot be generalized to the results.
- What are some other possible tables and/or graphs that we could create?
1. histogram could be an option.