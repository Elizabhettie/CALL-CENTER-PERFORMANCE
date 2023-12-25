# CALL-CENTER-PERFORMANCE

## INTRODUCTION#

This report provides a comprehensive analysis of the call center performance based on the dataset encompassing Call ID, Agent, Date, Time, Topic, Answered(Y/N), Resolved, Speed of Answer, AvgTalkDuration, and Satisfaction Rating. The analysis aims to identify trends, patterns, and areas for improvement within the call center operations.

## ABOUT THE DATA/DATA COLLECTION

It is a structured data, and it is a secondary data collected. The data contains a table in xlsx files. It contains 5000 rows and 10 columns.

The analysis to be carried out is to answer the following questions:

1.	How does the volume of calls vary over time?

2.	What are the top 3 days in each month with high call activity?

3.	How many calls fall into each category of the "Answered" variable (Y/N)?

4.	What is the percentage breakdown of calls by resolved status?

5.	What is the distribution of calls among different agents?
  
6.	How does satisfaction rating change over months?

7.	Can we visualize the distribution of calls across different topics?

## TOOL

The tool used is Microsoft Power BI for data cleaning and analysis.

## DATA CLEANING AND TRANSFORMATION

The following are the different cleaning procedures:

•	Split the ‘Date’ column into three columns and renamed them Day, Month and Year respectively. Changed the three columns’ data type to text format.

•	The 1, 2, 3 in the month column was replaced with January, February and March.

•	Changed the data type of the column ‘Time’ to Time format.

•	The Y and N in ‘Answered(Y/N)’ column was replaced with ‘Yes’ and ‘No’.

•	The Y and N in ‘Resolved’ column was replaced with ‘Yes’ and ‘No’.

•	Then made use of ‘close and apply’ for further analysis.
 
## DESCRIPTIVE DATA ANALYSIS(DDA) AND INSIGHT

For the analysis to be understood and the questions to be answered charts were created for it to properly analyzed for insights. The following consist of questions, its analysis and insight for each:

### 1.	How does the volume of calls vary over time?

The line chart illustrates the fluctuation in call volumes spanning from January 2021 to March 2021. Notably, January stood out with the highest volume of calls, reaching a total of 1,772. In contrast, both February and March demonstrated comparable call volumes, with February recording 1,616 calls and March slightly trailing behind at 1,612.
This visualization offers valuable insights into the patterns of call activity over the specified period. This chart helps us see when the call center is busiest. In January, lots of people called, but in February and March, the number of calls was similar. Knowing this helps the call center plan better to handle the number of calls each month and make sure customers get the help they need.

 ![CHART 1](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/fc9cbd6b-b1f5-4df5-870f-7d512e144a97)


The image above is the line chart created to show the volume of calls over time.

### 2.	What are the top 3 days in each month with high call activity?

The chart illustrates the top three days with the highest call activity in each month. Specifically, on the 1st of every month, there were 72 number of call activity in February, 64 in March, and 58 in January. Similarly, on the 11th of each month, the number of call activity was 72 in February, 74 in March, and 84 in January. On the 4th of every month, the call activity counts were 72 in February, 70 in March, and 54 in January.
Understanding this chart tells us which days are busy for the call center. It's clear that the 11th day, especially in January, consistently has a lot of calls. Knowing this helps the call center plan better for these days, making sure they have enough staff to handle the higher number of calls and provide good service to customers.
 
 ![CHART 2](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/099d3a12-8fe2-4ea6-8d6c-2422f9eb6d69)
 

A stacked bar chart was created to show the top three days with the highest call activity in each month.

### 3.	How many calls fall into each category of the "Answered" variable (Y/N)?

The chart provides a breakdown of call responses, distinguishing between answered and unanswered calls. Specifically, it indicates that 4,054 calls were successfully answered by agents, reflecting instances where customers connected with a representative to address their inquiries or concerns. Conversely, there were 946 unanswered calls, signifying instances where customers may not have been able to connect with an agent or experienced a prolonged wait time.
This clear delineation between answered and unanswered calls serves as valuable insight into the operational efficiency of the call center, allowing for a targeted analysis of factors influencing successful call resolutions and identifying areas that may require improvement to reduce the number of unanswered calls.

 ![CHART 3](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/3782b28b-0331-46a8-8e4a-c8496bf387f3)
 

The stacked column chart above shows the number of calls that fall into each category of the "Answered" variable (Y/N)
 
### 4.	What is the percentage breakdown of calls by resolved status?

The chart shows the percentage of resolved and unresolved calls. Out of all the calls, 3,646 got resolved, which is 73%. This means that for most calls, customers were able to get help from the agents. However, there were 1,354 calls that didn't get resolved, making up about 27% of all calls. This tells us there's room to improve and make sure more customers get the assistance they need.
Checking out this chart helps us see how well the call center is doing in solving customers' problems. Having 73% of calls resolved is good, but it also means that nearly 27% of calls didn't get the help they were looking for. This insight suggests there might be ways to make things better, like finding ways to resolve more calls or making it easier for customers to connect with the agents.

 ![CHART 4](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/d7fafba2-88d8-4f8b-9bee-6d9f41ffcaad)
 

The Pie chart above was created to show the percentage of resolved and unresolved calls.

### 5.	What is the distribution of calls among different agents? 

Jim handled the highest number of calls among the 8 agents, reaching 666, while Stewart handled the lowest number of calls at 582.
Breaking it down further, Jim handled 666 number of calls, followed by Martha with 638, and Dan and Diane tied at 633. Becky had 631, Grey had 624, Joe had 593, and Stewart handled 582 number of calls. Across all 8 agents, the number of calls varied from 582 to 666. This information gives us a glimpse into the number of calls each agent handled, with Jim managing the most and Stewart the least in the group.

![CHART 5](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/72cdab21-c41a-436d-9ce7-cee41d784104)


The stacked column chart above shows the distribution of calls among the agents in the call center.

### 6.	How does satisfaction rating change over months?

The line chart shows how the satisfaction rating changed from January 2021 to March 2021. In January, the satisfaction rating was the highest, reaching a total of 1,445. Then, in February, there were 1,298 and in March, it was a bit less with 1,301.
This chart helps us see how happy customers were with the service each month. January had the highest satisfaction rating, but it slightly dropped in February and March. Understanding these changes can help the team find ways to keep customers happy and maintain a good satisfaction rating.

![CHART 6](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/59493663-376b-441f-af1b-5e5159b8ab16)


The image above is the line chart created to show the trends of call satisfaction rating over the months.
 
### 7.	Can we visualize the distribution of calls across different topics?

The topic that got the most calls was Streaming, with a high count of 1,022. If we look closer, Streaming had the highest number of calls, followed by technical support with 1,019 calls and payment-related topics with 1,007. Admin support and contract-related topics were tied, both having 976 calls.
Understanding which topics customers call about the most, like Streaming, technical support, and payment issues, is valuable for the team. It highlights areas that may need extra attention or improvement to ensure customer satisfaction and effective support.

 ![CHART 7](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/ce418057-060f-4ac3-a0c3-8a483cd895a1)
 

The clustered column chart above shows the distribution of calls across topics.
 
## RECOMMENDATION

Following the analysis of the call center performance, several key recommendations emerge to enhance customer satisfaction.

Firstly, it is essential to address the instances of unanswered calls. Investigate the reasons behind these occurrences and consider optimizing staffing levels during peak periods, improving call routing mechanisms, or implementing strategies to reduce wait times.

Secondly, there is an opportunity to enhance resolution processes. While a substantial number of calls were resolved, consider implementing training programs for agents to improve problem-solving skills and streamline resolution processes. This can contribute to higher customer satisfaction and an increased number of successfully resolved issues.

The fluctuation in satisfaction ratings over the months suggests the importance of ongoing monitoring and analysis. Regularly assess customer feedback, identify patterns, and implement measures to maintain or improve satisfaction levels. This may involve targeted improvements in service quality, response times, or communication strategies.
By implementing these recommendations, the call center can work towards providing a more seamless and satisfactory customer experience, addressing specific pain points, and continuously improving performance based on customer needs and feedback.

## VISUALIZATION

![FULL CHART 1](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/fa84b1a5-448c-42a5-8a30-e2b294208b92)


![FULL CHART 2](https://github.com/Elizabhettie/CALL-CENTER-PERFORMANCE/assets/153202306/e1e8744e-9afd-4526-8e0a-5408fc4de249)

