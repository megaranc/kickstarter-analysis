# Kickstarting with Excel

### Analyzing kickstarter outcomes based on goals and outcomes based on launch date.

## Overview of Project

### Purpose

### The purpose of this project is to help an up-and-coming playwright, Louise, who wants to start a crowd funding campaign to help fund her play,*Fever*. By analyzing the data on Kickstarter dataset, we want to know how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### By visualizing campaign outcomes based on their launch dates and their funding goals, we are able to discover some interesting data trends.

### Analysis of Outcomes Based on Launch Date

### To better analyze and understand the data, we created a pivot table to examine the relationship between campaign launch date and campaign outcome.[Kickstarter_Challenge](path/to/Kickstarter_Challenge.xlxs) Then we created a line chart from the pivot table to visualize the data trend. [Theater_Outcomes_vs_Launch](path/to/Theater_Outcomes_vs_Launch.png) From the chart, it is clear that campaigns that start in late-May or early-June have a very high chance of being successful at meeting their kickstarter goals. On the contrary, campaigns that start in October have a very high chance of failing to meet their kickstarter goals. 

### Analysis of Outcomes Based on Goals

### Next, we tried to interpret the data by visualizing the percentage of successful, failed, and canceled plays based on funding goal amount. In order to analyze the relationship between funding goal amount and funding outcome, we created and computed a new table, "Outcomes Based on Goal". [Kickstarter_Challenge](path/to/Kickstarter_Challenge.xlxs) Then we created a line chart using the data computed to uncover another data trend. [Outcomes_vs_Goals](path/to/Outcomes_vs_Goals.png) From the graph, we can see that when the funding goal is set to be lower than 1000, a funding campaign has a higher chance to fail. When the funding goal is set between 1000 and 14999, however, a funding campaign has a very good chance of successing.

### Challenges and Difficulties Encountered

### One challenge that I encountered was the computation of "Outcomes Based on Goals" table using the command: =COUNTIFS. Because manually adding a filter in the original Kickstarter data sheet was not feasible, we had to type in filter commands within the =COUNTIFS function. The function is nothing too complex in any way, however, the process of computing it for different goal ranges requires a lot of attention and carefulness. 

## Results

### From the Outcomes based on Launch Date analysis, it is safe to advice Louise to set her funding campaign start date some time around the beginning of June. Based on the data, Louise's funding campaign is most likely to succeed with a start date around late May and early June; her campaign is most likely to fail with a start date in October. 

### From the outcomes based on goal analysis, we can conclude that it would be most wise for Louise to set her campaign goal between 1000 and 15000, or even between 30000 and 45000. Any goal amount other than the previously recommended amount signals a failure based on the data we have. 

### In my opinion, there are several limitation of the kickstarter dataset that we have been given. First of all, although most of the data are from this decade, they are still not recent enough. For example, consumer tastes can change dramatically over the course of just one year. Also, the economy and financial status of an average household in a country can change from year to year as well. These are all factors that can potentially affect the outcome of a possible funding campaign. Without detailed analyzation of every aspect of the given data, it might lead to us making false conclusions. Moreover, the dataset failed to distinguish different genres of all the shows. There might be a causal relationship between genre and outcome of funding campaign. For instances, the general public might prefer comedy over tragedy. 

### Therefore, one of the tables we can create is to find out the genre of each show and compute them with the campaign outcome of each. Then we can analyze if there are other hidden trends in our dataset. On another note, for Analysis of Outcomes Based on goal, a scattered chart would also be suitable when visualizing the data we have.
