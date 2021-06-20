# Kickstarting with Excel

## Overview of Project:
- We extracted all data based on the theater campaigns and created a pivot table to reflect the successful,failed, and canceled data by year and filtered by months. We then created a line chart to express these outcomes over time.
- The second part of this project included outcomes of the fund raising campaigns based on plays. Then this data was sorted by a range of fund raising goals set for these plays.

### Purpose:
The purpose of this analysis is to look for trends based on a subset of the main data set. More specifically, we were looking to see if the goals of these fundraising campaigns had a significant impact on the result.

## Analysis and Challenges:
### Analysis of Outcomes Based on Launch Date
We pulled a portion of the data from the main data set to look for trends between the dates these campaigns were started and the results of these campaigns.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/83428759/122684313-51265e00-d1ca-11eb-9ff1-c9a4b4255799.png)

### Analysis of Outcomes Based on Goals
The second portion of the data that was pulled was based on a range of goals set for each outcome (successful, failed, canceled) and whether the initial goal had an impact on the result of the campaigns involving plays.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/83428759/122684376-a7939c80-d1ca-11eb-9a7f-73ae38bf49c7.png)

### Challenges and Difficulties Encountered
The challenges I had faced while working through this project was determining how to write the correct functions for the goal ranges on each outcome so that this could be expressed correctly on the data chart.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

Overall, the majority of the data based on theater campaigns were successful, but we can see that there was an increase in successful campaigns in the months of May and June.

- What can you conclude about the Outcomes based on Goals?

The percentage of the successful and failed campaigns based on the total projects in each goal category was affected by the goal price range set for the campaigns. The higher the goal was for the campaign, the less likely it would be successful. We can see that the percentage of successful campaigns trended downward as the goal of each project increased. We can see that the campaigns with goals less than 1000 and between 1000 and 4999 had a relatively high rate of success, but this starts to trend downwards when the goal was set above 5000. We can also back this up based on the failed percentage, this percentage trended upward when the pledge goal increased.

- What are some limitations of this dataset?

This data set only looks at theater and play campaigns, it does not include any other factors from the main data set. We do not know if all campaigns were affected by increased goals, where there could be other factors that affected the results of these fundraising campaigns.

- What are some other possible tables and/or graphs that we could create?

We could analyze the same set of paramaters based on food campaigns, and see if there is a trend of successful and unsuccessful campaigns based on the goal ranges set for these projects.
We could look at these fundraising projects based on location, and look to see if there is a correlation of successful campaigns based on the parent category. We would create this analysis by looking at specifics parts of the data where campaigns are more popular than others based on location. For example we could look at number of successful food based campaigns in each country.
