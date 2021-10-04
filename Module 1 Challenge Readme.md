# Module 1 Challenge - Kickstarting with Excel

## Overview of Project & Purpose

The purpose is to find out how different campaigns fared in relation to their launch dates and their funding goals. Narrowing the scope for Louise to see clearly and visually the results of each graph, particularly for her interest in theater “plays” category, is essential to quickly discerning the data. Marking the visual landscape by creating pivot tables, charts and graphs summarizes and quickly establishes success, failure, and cancelations. These multiple categories of variables, determining length of fundraising campaigns, its start and end date, amount invested, etc, all contribute to determining crucial information for Louise’s campaign, or more importantly, her vision. 

## Challenges and Difficulties Encountered

Using the COUNTIFS formula allowed me to include several criteria to be met inside each cell for the Outcomes Based on Goal data set. Specifying “plays”, and its success or failure, and the goal amount ranges were aspects of the COUNTIF formula in Excel that I used in order to display the data set that was wanted. Inputting the data for the ranges proved tedious, because I didn't realize you can freeze a column letter with the dollar sign adjacent to it, so that you can copy over the same formula to the next column without Excel switching columns. For example, if I put $F:$F vs F:F, and copy that into a new cell it will retain those letters without switching them. 

Also, after creating a chart for the second deliverable, I ran into an issue in placing the correct units and value to the y axis, and with having excess data for the chart. After discovering the Select Data button under Chart Design, which only activates when the chart is clicked on, I found I could press “-“, a subtract key adjacent to the plus button, to filter out only the percentage data, and also press the “switch the rows and columns” button to fit my needs for the true result. 

There was ultimately no real challenge with creating both charts for deliverable 1 & 2, but instead more so was there a challenge for me with regard to the written interpretation of the graphs for deliverable 3 that I'm writing here. It has not been touched on much in class, for interpreting in paragprah form the data we are making and its meaning. It is crucial to be able to understand the information a chart is presenting, and interpret that into unambiguous statements concisely and clearly. This I struggle with unless given guidance.

### What are two conclusions you can draw about the Outcomes based on Launch Date?
The most successful time to launch the campaign was in May-June.

The number of failed launches is relatively consistent over time whereas the number of successful launches has a definite peak.

### What can you conclude about the Outcomes based on Goals?

The higher the dollar amount of the goal, the less likely for the campaign to succeed. 

### What are some limitations of this dataset?
Referring to the Outcomes Based on Goals worksheet, the percentages of successes and failures for higher goal amounts is greatly distorted, causing it to be skewed, because of the low total number of projects. When there is too little data, or an asymmetry that deviates from the symmetrical bell curve, or normal distribution, it is difficult to draw conclusions about the data set for Louise. 

### What are some other possible tables and/or graphs that we could create?

Using the midpoint of the goal ranges and calculating the dollars of successful campaigns vs the dollars lost through failed campaigns we can make a stacked bar chart to show the relationship of failed dollars to successful dollars. For example, we can easily interpret visually that for goal amounts under 10k, the dollars generated are estimated to be higher. So, the potential estimated value of successful campaigns is greatest for campaigns with goals under about 15000 dollars. 

We could also explore more with the Box and Whisper Chart that was created in 1.5.4 and filter other variables, aside from just "GB" as country and subcategory “musicals”, we could explore other options to help us visualize our data to determine outliers and ranges, that would lead us to draw conclusions given a different connecting set of variables. 



