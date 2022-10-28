
# Kickstarting with Excel

## Overview of Project

### Purpose
Purpose of the analysis was to a) determine the relationship between successful theatre revenue outcome and the date of launce and b) determine the relationship between the revenue outcome and the goal established. 
## Analysis and Challenges
My significant challenge was proper use of the COUNTIFS() function. For example with the successful vs failed analysis:
=COUNTIFS(Sheet1!F2:F4200,Sheet1!F2,Sheet1!D2:D4200,"<1000",Sheet1!P2:P4200,Sheet1!P522)

The easiest way to complete the table for me was to copy and paste the formula, changing either the dollar range or the "successful" vs "failed category, but the cells had to be manually adjusted while doing this. There is propably a way to mitigate the manual adjustments needed with the copy and paste method, but I was unable to find it quickly. 
### Analysis of Outcomes Based on Launch Date
![image](https://user-images.githubusercontent.com/116207878/198478335-c8d469bd-c686-4334-9b2a-b8d952288bf5.png)

### Analysis of Outcomes Based on Goals
![image](https://user-images.githubusercontent.com/116207878/198478008-cfca8784-0c67-45dc-9cb3-d9d1fa5c0d8a.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Successful1 theater outcomes occurred most often in the spring, particularly in the May June and July launch dates
2. There seems to be little correlation of launch date with failed theater outcomes

- What can you conclude about the Outcomes based on Goals?

Goals higher than 45,000 are associated with high failure outcomes

A sweet spot of greater than 60% success rate seems to be between 35,000 $45000 goals

- What are some limitations of this dataset?
The relatively higher success rate seen at goals between $35,000 and $45,000 is unexplained by this limited analysis; was it related to launch dates in any way?
- What are some other possible tables and/or graphs that we could create?
1. One could look at the correlation/interaction between goal AND launch date with positive outcomes
2. One could examine the relationship between type of play (comedy, non-fiction, etc) to positive outcome
