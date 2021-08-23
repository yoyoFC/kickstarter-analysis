# Analysis for theater campaigns: launch day and funding goals

## Project Overview
### Purpose
The purpose of this analysis is to provide statistic information to our client Louise regarding how theater campaigns fared on their launch and their funding goals. 
We are going to analyze 1047 samples between the period of 2009 to 2017 to obtain a close view about the correlation between goals and launch date, including suggestions for the client.

## Analysis and Challenges
### Procedure
This analysis started with a data sample of 4114 kickstarts campaigns, which included information about launching date, financing goals and results labeled as “outcome”. 
The first step was to organize the data in an accessible and understandable way. In some cases, I had to modify the column format and in others, re-use the information available to create new column for a better data understanding (i.e. convert UNIX time stamp in human-readable format).

<img src="https://user-images.githubusercontent.com/88695570/130395190-11dd648c-bc19-4c1d-b21c-90bc11092a9f.png" width=80% height=80%>

The second step was to filter the data based on the client’s needs: goals and the subcategory “plays”. Finally, with this filtered information I was able to build charts and tables to visualize the results. 

<img src="https://user-images.githubusercontent.com/88695570/130394285-fd404d05-a171-4e5f-9d5f-8c4c85961edf.png" width=70% height=70%>

### Challenges and Difficulties Encountered
I found two specific difficulties. Both difficulties were solved by finding examples on the web.

* **Parameters for some of the excel functions:** It is very important insert the correct values for the parameters because excel does not describe where could be the syntax error.

<img src="https://user-images.githubusercontent.com/88695570/130396129-26c75c62-4776-4dc7-b471-55a1923b97a1.png">

* **Cosmetic details on the charts:** I found some difficulties editing the legends and the resizing the chart space. 

<img src="https://user-images.githubusercontent.com/88695570/130396132-bde85445-47dd-478d-aefe-60cb9f0c82ee.png" width=40% height=40% >

### Analysis of Outcomes Based on Launch Date

1. There is more probability of success if the launch date is between April and July.
2. The successful and failed curves tend to come together during December. This indicates that during this month there will be around 50% of probability for failure. I would recommend to not launching the play at the end of the year.

<img src="https://user-images.githubusercontent.com/88695570/130397342-2af1d9ec-091f-4a33-a969-1bfe1fbe42cc.png">

### Analysis of Outcomes Based on Goals
1. The biggest successful percentage is registered when the goal is lower than USD 1,000.00.
2. The second highest successful percentage appears when the goal range is between USD 1,000.00 and USD 5,000.00. There is an important detail, the sample quantity available for this range is 534 projects which represent a little bit more than the 50% of the entire sample group for “plays” in theaters. 
We can deduce that the projects with a goal lower than USD 5,000.00 in funding are the most common in the market and end up obtaining a greater success result.
3. As the goal value increases, the chances of success decrease up to the point where it becomes a complete failure. I would recommend our client to consider a limit of USD 20,000 to obtain better results.

## Dataset Limitation
### Up-to-date Kickstart data
Ideally, I would like to analyze more recent data (the newest data was registered in 2017). With new data, I would be able to provide observations and suggestions according to the current year. 

### Theater style
Another limitation that I found on the dataset is the theater style for the campaigns: tragedy, comedy, melodrama, and drama. In order to make a deeper analysis, I think it is important to consider this type of information because it will help our client to get a better idea of how her campaign will be accepted by the public.

### Theater plays life time
In my opinion, the dataset is missing information of how long the play was on the billboard. This would also give us information on how long the project was sustained over time.

## Other possible tables and/or graphs
1. There are other two ranges where the successful percentage is over 50%: USD 35,000.00 to 40,000.00 and USD 40,000.00 to 45,000.00 .
Combining these two ranges, the total number of projects is 9. Despite of the small dataset in comparison with the projects in other ranges, this is still valuable information for our client. We can conclude that if the project has a goal over USD 35,000.00 the expected number of backers should be the highest possible.

2. We have the information of the funding campaign period (start and end date). By subtracting these dates we can obtain the total number of days.  
In this table we can notice that the average days for a successful campaign is around 30. This information might not be relevant when the client would like to know more about the “launch date correlation”, but it is a valuable reference for future projects.

3. The mean of backers for a successful theater campaign based on the dataset is 56 and the median value is 39. This is the range where our client should consider the number of backers for her campaign. 
As an additional comment, the maximum number of backers found is 930. This result can be considered as complement for the comments on the section 6.1

4. It is possible to provide an overview of the data distribution based on the successful goals for “plays”. From this plot, I can suggest to produce the plays for less than USD 4,101.00 
 
