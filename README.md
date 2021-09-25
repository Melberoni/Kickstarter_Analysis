# Kickstarting with Excel

## Overview of Project

Louise wants to start a crowdfunding campaign for her new play Fever, she has estimated a budget of $10,000. She wants to know if there are specific factors that make a Kickstarter campaign successful. We have a dataset of crowdfunding information from the website Kickstarter.  This is broken down into different types of crowdfunding projects and includes variables such as goal amount, pledged amount, country, how many backers and if the project was successfully funded or not.

### Purpose
The purpose is to identify factors that make a Kickstarter campaign successful and provide this information to Louise so she can mirror these in her Kickstarter.

## Analysis and Challenges
The Challenge was to analyze outcomes of different campaigns in relation to their launch dates and funding goals. 

### Analysis of Outcomes Based on Launch Date
The graph below shows the Kickstarter data filtered down to theater campaigns only. The Y axis is the number of campaigns and the x axis has the month of the launch date. The colors of each line indicate successful, failed, and canceled campaign. 

![outcomes vs Launch Date](resources/Theater_outcomes_vs_launch.png)

### Analysis of Outcomes Based on Goals

The graph below shows the percent of each outcome compared to the goal of all the campaigns for plays only. Percent of total campaign is on the Y axis and the goal of each campaign is on the x-axis. The colors of the line indicate the outcome of the campaign. 

![Outcomes based on Goals](resources/Outcomes_VS_Goals.png)

### Challenges and Difficulties Encountered
One challenge that I encountered was with the outcomes vs goals campaign graph. My graph was initially like the expected output but not exact (see image below) my number of canceled was too high.

![incorrect_image](resources/incorrect.png)

I checked my logic over and over again and it seemed correct so in office hours before class I asked if anyone else had similar issues and one person had the exact same problem as me and it made me feel like I was not wrong, but as the small group inspected our code another classmate noted we forgot to add the filter for "Plays" (see image below)

![incorrect_code](resources/incorrect_code.jpg)

Im very glad I go to class early and spoke up as this was a minor issue that was easily fixed but would have cost me some points on this challenge.


## Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?
- Theater outcomes have more successful campaigns than failed or canceled combined.
- The month of May seems to have the most launches and therefore has the most successful outcomes. 
- The total number of campaigns decreases as you go into fall and winter, there   are also fewer successful campaigns going into winter.

#### What can you conclude about the Outcomes based on Goals?
- Generally speaking, the Percentage of successful campaigns decreases as the Goal of the campaign increases.
- For the $35,000 to $39,999 and the $40,000-$44,999 ranges of goals there were only a small number of total campaigns in each bucket compared to lower goals, so the few that were successful increased the percentage to 50% and may not be representative of the entire population of campaigns 
- It seems that those campaigns with a goal under $15,000 have the best chance of being successful.

#### What are some limitations of this dataset?
- This data set only shows the outcomes of the crowdfunding campaign, it doesn’t show if the project was successful in the real world, for example if a play was good, or if a food truck made money etc.
- You don’t know if the backers of the different campaigns are family and friends of the person starting the Kickstarter or just random people
- It doesn’t include any information about how each person promoted their Kickstarter, if at all.

#### What are some other possible tables and/or graphs that we could create?
- It would be interesting to see how many backers successful campaigns had vs failed campaigns
- I would also like to know more about the spotlight and staff pick variables, does having that as true mean you’re more likely to have a successful campaign?
- Average donation vs goals

