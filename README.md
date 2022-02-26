# Kickstarter_analysis
Analyzing Kickstarter campaigns.

## Overview of the Project.
The purpose of this project is to learn how to take advantage of Excel as a tool to solve real problems. We are going to use some Excel features that will help us to manage databases in an easier and faster way, to get answers more efficiently and create attractive visualizations for an effective communication of our findings.
In this case we are going to help Louise plan a funding campaign for his Fever play, she wants to raise over $10,000 so we are going to analyze the Kickstarter database to uncover patterns that can help her to achieve her goal, specifically we are going to focus on the possible   influence of the launch date and the intended goals. The point is to determine if these two factors have more impact behind the success of a crowdfunding campaign. We are working with a Kickstarter Database, that contains all the campaigns that have been created around the world, the purpose of each one, their amount goals and final pledge, the number of supporters and the date they were created and ended. 

## Analysis and Challenges
### Overview of the analysis.
In order, to help Louise, we needed to organize the data to find those campaigns with more similarities with the one of Louise, so we started to filter the campaigns based on the categories, to get only the ones about "Theater" and "Plays". 

#### Outcomes by Launch Date
We created a pivot table so we can extract all the info of just "PLAYS" and we could analyze the outcomes based on the launched date, we even can filter by Year, so can check how the outcomes change over the years or look for the months with more successful outcomes and avoid those with more failures. Based on the pivot table we got a graphic where we can see the relationship between the outcomes and the launch month even per year. 

 ![image](https://user-images.githubusercontent.com/43548929/155852534-e2110311-177c-4c0e-92ca-3d714a49707b.png)
 ![image](https://user-images.githubusercontent.com/43548929/155852544-5b702bbd-2569-48af-b66c-cc4217ad6aac.png)
 
#### Outcomes based on Goals.
To analyze the funding goal amount and how they determine the outcomes, we created a new worksheet with a Table to display the number of successful, failed, and canceled campaigns according to their amount goal, we used a" Countif function" to filter under 3 conditions, we only need to know about the "Plays" outcomes in certain amount range. Then we calculate the percentage of each outcome so we can get a graph that shows the relationship between them.

![image](https://user-images.githubusercontent.com/43548929/155852571-005f394a-de74-45e9-ba76-1a505627f49f.png)
![image](https://user-images.githubusercontent.com/43548929/155852575-986c448b-d9b2-45d2-b4f6-edb98cb953a3.png)

### Challenge.
Once you create a pivot table there are some limitations to interact with the cells on it, or at least I don't how to do it. For example, I was trying to get the percentage of Successful Campaigns by month, I got it for January, but when I tried to replicate it for the whole column, the reference of the cell inside the Pivot Table didn't move, they just copy the same value and I have to do it manually for each month.

## Results
### Conclusions of Theater Outcomes by Launch Date.
   1) The most favorable month to launch the campaign is May, it is the one with more successful campaigns and the one with the higher ratio, having around 2/3 of successful campaigns, so if you launch in this month you will have like 66% chances of having a successful campaign. If you can't make it by May then June will be your second-best option. The number failed campaigns are in a range between 30 and 50 throughout the year, there's no big difference so we just need to focus on the peaks of the successful line.
   2) We need to avoid the last quarter of the year to launch, as we can see there's a small difference between the number of successful and failed campaigns, especially December where you have the same chance to fail or succeed, and it's the month with the lowest successful campaign. 
   
### Conclusion about Outcomes based on Goals.
The campaigns with the lowest amount goals are more likely to reach their goal, over 70% of the campaigns under $4,999 are successful. In general, we can see a negative correlation between the amount-goal and the outcomes, with an exception for the campaigns raising between $35,000 and $39,999 there's again a 67% chance that you reach your goal, but there are only 6 campaigns on this range the sample is small. Louise's campaign is over $10,000 so her probability of success is 54%.

### Limitations and Recommendations for the Database.
For the Outcomes based on Launch date I would recommend getting the percentages for each outcome, I did it, and its easier to choose the best months, after 66% on May and 65% on June, we can expect a 63% chance of success if we launch either on May, April, or July. 






