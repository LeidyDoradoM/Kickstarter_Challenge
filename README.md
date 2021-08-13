# Module 1: Kickstarting with Excel

Louise is a promising playwrighter who wanted to start a crowdfunding campaign to help her fund her play **Fever**.  After an initial analysis she set a campaign that is close to meet her initial goal in a short period of time. She is very excited about how her play fundraising is going but now, she wants to gather more information to understand better how another factors could impact her campaign.

## Overview of Project

To help Louise set her fundraising campaign to success, we need to analyze crowdfunding data so we can understand how these campaigns behave from start to finish. Our interest is campaigns that are in the same category of Louise's, this is *Theater*.  In addition, Excel is used to organize the data and to show data trends and patterns as charts that give a better grasp of its behavior.

### Purpose

The goal of this analysis is to get insights about how the **Launch Date** and **Financial Goals** of fundraising campaigns in Theater Category impact their success.

## Analysis and Challenges

The Crowdfunding data originally comprises information about fundraising campaigns in different categories such as television, technology, theater, etc. Because Louise's interest is Theater plays and too many data could clutter important information, we need:

1. Filter out the original crowdfunding data so only data in the Theater Category is considered in the analysis.
2. Once we are focused on the data of our interest, and if the analysis requieres, we need to make calculations or perform some process that allows to visually capture the behavior of these campaigns respect to  **Launch Date** and **Financial Goals**.

### Analysis of Outcomes Based on Launch Date

Our first analysis is concerned with how the fundraising campaigns outputs depend on their Launch date.  We consider three types of outputs: *Successful*, *Failed*, and *Canceled*.  Figure 1 shows a line chart based on data from a Pivot table whose rows are the months of a year and columns are the counting of campaigns. Each line represents the campaigns in the Theater Category that were successful, failed or canceled respectively.

![LaunchDate](https://raw.githubusercontent.com/LeidyDoradoM/Kickstarter_Challenge/main/resources/Theater_Outcomes_vs_Launch.png)

At first glance we can see that in the Theater Category most of the fundraising campaigns have been a success and that the number of canceled campaigns is very small comparing with the number of successful campaigns.  This trend could be confirmed by the numbers in the pivot table presented in the **Theater Outcomes by Launch Date**  sheet in the Excel file ![worksheet](https://raw.githubusercontent.com/LeidyDoradoM/Kickstarter_Challenge/main/Kickstarter_Challenge_Copy.xlsx).

### Analysis of Outcomes Based on Goals

The second analysis we performed in the crowdfunding data refers to how the campaigns fare with respect to their financial goals.  Again, *Successful*, *Failed*, and *Canceled* campaigns were considered as well as 12 different ranges of dollar-amount.  Because we are only interested in theather plays campaigns, we first filtered out the data such that only *Plays* subcategory is considered in the analysis.  

In order to analyze this relationship, we computed the percentages of campaigns that were *Successful*, *Failed*, or *Canceled*. To do this calculation, the total number of plays-campaigns and the number of campaigns in each output category and in each dollar-amount range goal were considered. Figure 2 shows how the percentage of successful, failed or canceled campaigns vary with respect to the dollar-amount ranges.

![Goals](https://raw.githubusercontent.com/LeidyDoradoM/Kickstarter_Challenge/main/resources/Outcomes_vs_Goals.png)

In this figure we can observe that within the Theater campaigns that were canceled, none of them was in the subcategory plays (the line in gray color is a straight line in 0%). Also that at each amount-dollar range, the percentage of successful and failed campaigns are complementary (the sum of both values corresponds to the one hundred percentage); this is why the two lines in blue and orange color have an opposite behavior.

### Challenges and Difficulties Encountered



## Results

* What are two conclusions you can draw about the Outcomes based on Launch Date?

According to this line chart, most of the theater campaigns have been  a success in collecting their funds. May is the best month of the year to launch a fundraising campaign and on the contrary, December is the worst month.

* What can you conclude about the Outcomes based on Goals?

None of the plays campaigns were canceled. Campaigns with financial goals less than $15,000 are a success as well as campaigns with goals between $35,000 and $45,000. The trend of percentage of fails is exactly opposed to the trend of percentage of successes.

* What are some limitations of this dataset?

* What are some other possible tables and/or graphs that we could create?

We can try to specify the outcomes to see different behaviors based on the country in which these campaigns are launch.