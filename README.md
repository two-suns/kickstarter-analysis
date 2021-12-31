# Kickstarting with Excel
## Overview of Project
### Purpose
Louise's play <i>Fever</i> quickly came close to meeting its fundraising goal.  Now, she wants to know how Kickstarters performed in relation to their launch dates and funding goals.  The purpose of this analysis is to determine how Kickstarter campaigns performed in relation to their launch dates and funding goals specifically in the theater and play categories.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
More successful outcomes occurred when theater campaigns launched in the month of May.  June is a close second with only 11 fewer successful outcomes.  This may be due to the fact that schools and colleges have let out for the summer and more people are available to attend theater productions.  

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/59906657/147778106-090d4704-6a9e-43b7-b4d1-2ed0d95bb668.png)

<i>Graph showing theater outcomes based on launch date.</i>
### Analysis of Outcomes Based on Goals
Kickstarters were more successful in reaching their goals when they were kept below $5000. Both buckets containing this range are above 70% and they have statiscially significant amounts to assess.  As the goal amounts increase, the failed percentage increases accept in the $35000 - $45000 range.  

<img width="466" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/59906657/147778335-25b7cbb1-705f-4935-9d16-42d88d890e9b.png">

<i>Graph showing outcomes of theater plays based on goals.</i>
### Challenges and Difficulties Encountered
The biggest challenge faced was getting the arguments for the COUNTIFS function organized and formatted correctly for the different buckets.  For easier copying and editing of the function, absolute cell references to the Kickstarter sheet were used.  I was also briefly challenged by the pivot table row data.  I did not realize that three items were automatically added when dropping the date created conversion field into the rows area.  However, I quickly remembered to remove the unneccessary fields.
## Results
To conclude, if Louise wants to improve her chance of success, she should launch in May or June.  These are the months when the most successful theater Kickstarters were launched.  Also, May has the highest number of failed campaigns.  However, the summmer months have more total launch dates so more variations can be expected.  

If Louise wants to successfully meet her goal, it would be best to keep it under $5000 since this range had a greater percentage of successful outcomes.

A limitation to the dataset is the amount of data available for these specific categories.  I would feel more comfortable making these assessments with a greater amount of information.  

For theater outcomes based on launch date, the subcategory filter could be added to further narrow down types of theater Kickstarters.  The outcomes based on goals could also be represented with a stacked bar chart.
