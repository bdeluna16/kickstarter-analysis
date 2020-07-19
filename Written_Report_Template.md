# Kickstarting with Excel

## Overview of Project
A playwriter named Louise created a kickstarter campaign in order to raise funds for her play "Fever". She came close to her fundraising goal in a short amount of time and now wants to know how different campaigns fared in relation to their launch dates and their funding goals. 

### Purpose
Analyze kickstarter campaign outcomes for the category "theater/play" based on launch date & fundraising goals. Our analysis will provide Louise insight on the performance of other campaigns. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
* 
* The data in the graph is comprised of all "successful", "failed", and "canceled" kickstarter campaings in all countries from 2009-2017. 
* Looking at the trend line for theater outcomes based on launch date we can see that May and June have the highest number of successful kickstarter campaigns in the "theater" category. The trend line continually declines after June indicating a decrease in the amount of sucessful theater campaigns as the year goes on.

![image](https://user-images.githubusercontent.com/67936161/87866858-669c6380-c93b-11ea-8138-39ecd261c39a.png)

### Analysis of Outcomes Based on Goals
* The data in the graph below is a measure of the outcomes of kickstarter campaings in the "plays" subcategory vs. fundraising goal.
* To get the data we got the count of successful, failed, and canceled, campaigns for "plays" for the ranges in the image below. We then summed up the count of campaigns for each range and got the percentage of successful, failed, and canceled campaigns. 
![image](https://user-images.githubusercontent.com/67936161/87868278-175d2f80-c949-11ea-8413-ea50c53ec756.png)
* Kickstarter campaigns with Goals of less than $1000 & $1000-$4999 had the highest amount of successful campaigns. 
* 76% of campaigns with goals of less than $1000 were successful and 73% of campaigns with goals of $1000-$4999. 
* Campaigns that asked for $25000-$29999, $30000-34999, $45000-49999, & more than $50000 had the highest percentage of failures.
* $25000-$29999 had 80% fail, $30000-34999 had 73% fail, $45000-49999 had 100% fail, greater than $50000 had 88% fail

![image](https://user-images.githubusercontent.com/67936161/87868383-e6312f00-c949-11ea-85f2-f9c272932e22.png)

![image](https://user-images.githubusercontent.com/67936161/87868397-fcd78600-c949-11ea-845f-8aa4b3107e93.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  * Kickstarter campaigns launched in May had the highest amount of successful campaigns. 
  * There is a decline in the number of successful campaings launched in the months following May. 
  * Overall there is a greater probability of having a successful campaign launched in either May or June and a lower probability of a successful campaign if launched towards the end of the year.

- What can you conclude about the Outcomes based on Goals?
  * Campaigns that asked for the least amount of money saw the highest amount of successes. 
  * Overall the more money a campaign asked for the higher the probability of failure.

- What are some limitations of this dataset?
  * When measuring outcomes based on goals I found that the total number of campaigns for a given range was very little in comparison to other ranges. For example, the number of campaigns that asked for $45000-49999 was 1 which led to a 100% fail rate. A sample size of 1 will not provide an accurate depiction of the overall behavior of campaings in that range and can skew the data. To get a better overall picture of the outcomes for campaigns in ranges that have little data we would need a larger sample size.

- What are some other possible tables and/or graphs that we could create?
 * Line chart with markers
 * Stacked column chart
