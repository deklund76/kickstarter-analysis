# Kickstarting with Excel

## Overview of Project

This is an analysis of Kickstarter data for the purpose of aiding a client with a Kickstarter campaign for a play. Data from hundreds of kickstarter campaigns has been analyzed to visualize campaign outcomes based on both launch date and goal. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/44558170/123374545-e1f39580-d54c-11eb-83bd-781263b459a8.png)

The chart above shows the amount of successful, failed, and canceled theater-related kickstarter campaigns based on their launch date. Not the sharp rise from April to June follwed by fewer successful campaigns in the following months.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/44558170/123374524-d902c400-d54c-11eb-8c34-c09e30dba351.png)

This chart shows the percentage of campaigns that were successful or failed given their goal dollar amount. Note how the successful and failed campaigns swap places over the middle of the chart. There's also a dive for the $5000-$9999 range for which we have no data to even draw from.


### Challenges and Difficulties Encountered

One of the tricky challenges with making a chart in Excel without a pivot table is that you can't just grab and pull from all of the data especially when you are dealing with raw, or intermediate values that are used for calculating what you actually want to represent in a chart. This was a mistake I made when making the chart, "Outcomes Based on Goals" above. While entering the formulas to calculate the values in the spreadsheet, I also accidentally forgot the '$' to make some of the columns I was referencing fixed instead of relative which slowed down the process a fair amount.

## Results

The first conclusion that we can draw from this analysis is that May seems to be the best month to launch a theater related Kickstarter campaign. It has both the highest number of successful campaigns and the greatest proportion of successful campaigns compared to failed campaigns launching the same month. December, on the other hand, is not such a great month. This could be due to December containing the peak of the holiday season. When it comes to campaign goals however, it seems there is little correlation between success and the goal amount except at the extremes where campaigns with smaller goals that are easier to meet succeed more often while campaigns with huge funding goals appear less likely to be successful. One of the limits of the dataset is that a significant majority of campaigns, at least when it comes to plays, have goals under $5000, so it's difficult to draw meaningful conclusions about large scale projects. There are multiple goal ranges lacking any data that leave holes in the big picture. Considering this, it might be worthwhile to make charts from the entire data set (not just the play category) to help fill in these gaps especially if it supports what we've already found in our analysis of theater and play campaigns.
