# Kickstarting with Excel

## Overview of Project
The dataset provided shows different kickstarter projects throughout multiple industries.
We will be performing analysis on Kickstarter data to uncover trends, and this way, help make informed decisions.
Louise, our client, would like to know how the results of different kickstarter campaigns based on their launch dates and funding goals.

### Purpose
The purpose of this challenge is to uncover trends of other kickstarter campaigns in the theater category, and visualize campaign outcomes based in two variables:
- Their launch dates
- Their funding goals
 

## Analysis and Challenges
Since Louise is only interested in the outcome of theater campaigns, as these are the ones she can compare to her kickstarter project, we will be focusing on those.

### Analysis of Outcomes Based on Launch Date
We can clearly see that May is the month with more projects in total, and this is probably why it's the month with more failed and also successful projects. If we take a look at the amount of projects launched in May, it is specially striking the amount of successful projects in comparison with the rest of the year.

### Analysis of Outcomes Based on Goals
When we analyze the kickstarter projects based on their goals, we can quickly determine that projects with a lower monetary goal are in general way more successful. But we need to deep a little bit deeper in our data.

- We can see that the goal-bracket where more projects become successful is one of the lowest ones, that has goals from 1000 to 4999, followed directly by projects with goals lower than 1000.

But we also see that there is not as much data for projects with larger goals, which could make our analysis be bias. We will look more into this just below.


### Challenges and Difficulties Encountered
First of all, we had to find out the years of each campaign, so we created a new column and used a function to extract the year from the “Date Created Conversion” column.

Then we created a pivot table and filtered based on "Parent Category" to only show Theater campaigns, and "Years" to show only the industry that would affect or influence the decisions made by Louise.

We also filtered out the "live" outcomes, as we are not interested on that metric right now.

All the above is part of the analysis, but definitely a challenge we have, as mentioned briefly above, is the few examples we have for kickstarter campaigns in the theater industry for larger goals.

- What we did to overcome this difficulty is to compare successful, failed and canceled kickstarter projects by each goal, and then compare them using the percentage of how much each category weighted on our analysis. You'll be able to see this on the chart below.



## Results


- What are two conclusions you can draw about the Outcomes based on Launch Date?

-- First of all, 

![Outcomes based on Launch Date](https://github.com/sofiwolfes/kickstarter-analysis/blob/main/Challenge/Resources/Theater_Outcomes_vs_Launch.png)

- What can you conclude about the Outcomes based on Goals?

![Outcomes based on Goals](https://github.com/sofiwolfes/kickstarter-analysis/blob/main/Challenge/Resources/Outcomes_vs_Goals.png)

- What are some limitations of this dataset?
        (((	There is a summary of the limitations of the dataset, and there is a recommendation for additional tables or graphs (2 pt).)))

- What are some other possible tables and/or graphs that we could create?


Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.
