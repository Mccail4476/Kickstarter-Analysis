# UCSD Data Science Bootcamp Module 1

Remote Repository for Module 1

# An Analysis of Kickstarter Campaigns.
Performing analysis of Kickstarter data to uncover trends for Louise.
---
![Outcomes Based on Launch Dates](https://user-images.githubusercontent.com/99565016/154422951-5e521aa6-a077-44ee-9886-8f63f751a5e1.png)

We see from the above image that Kickstarters have a high success rate in May.
---
![Parent Category Outcomes](https://user-images.githubusercontent.com/99565016/154423042-52301f37-d604-4d75-bd60-247f76bf6b77.png)

We see from the above image that Theater was the most popular Parent category of the Kickstarters.
---
![Goal vs PLedge Whisker's Graph](https://user-images.githubusercontent.com/99565016/154426354-8ebf5469-b8b8-4bbc-b6b8-d45cba496051.png)

We see from the above image that many kickstarters have low pledged donations that's less than $4000.
---
It's recommended that Louise picks a play in Great Britain for Theater but keep the Kickstarter goal below $4000. Anything greater than a $4000 goal yields low pledged donations.

---

# UCSD Data Science Bootcamp Module 1

Remote Repository for Module 1

**Overview** 
We explore how different kickstarters performed in regards to their launch dates & their respective funding goals. Following up on that is 
to visualize any trends we find. The purpose behind this is so Louise can determine when is the optimal time range & goal range that successful theater
kickstarters have in common. By using Excel commands, we can sort the data to explore any trends hidden in the numbers.

**Analysis and Challenges**  

Visualization of Trends
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99565016/154824779-6d0a1d0e-0486-4f46-a084-748c6bb2af2b.png)
*From the image above, we can see that May has been a favorable time of the year to have successful theater kickstarters. It's interesting that the peak successful time range is during the summer & hits its trough during the winter time.*

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99565016/154824842-0f114bb2-3619-4924-b1d2-860e7a88a8a0.png)
*From the image above showing kickstarters for plays, it is clear that the percentage success rate shows an opposite trend than the percentage failed. Based off the image, we can see that the best goal range to work with is <$1000 & values between $35000 and $44999. It also appears that asking too high of a goal leads to <20% success rate, which isn't ideal for Louise.*

Difficulties

For this data analysis report, the hardest struggle for me was configuring the "ifs()" as  I didn't realize I had to filter out
'plays' in the command. I was under the impression if I filter out the 'plays' on the 'kickstarter' raw data sheet, the 
'=ifs()' would account for it. After trial & error through the Excel, I was able to get the correct diagram. Another difficulty was writing the '=ifs()' in a way that I did not need to repeat the script over and over for all goal ranges & percentages. Through time & perserverance with the help of the video provided in the module, I was able to complete the challenge.

**Results** 

Outcomes vs Goals

We can see that different factors can give Louise an idea of how well a 'play' kickstarter will perform based off of historical data. It's important to consider these factors as it will give a better probablity that her next Kickstarter will succeed. Thanks to the data visualizaton on the 'Outcomes vs Goals' display, she would know that asking for $25000 through $35000 or asking for anything greater than $45000 would be setting herself up for failure. Thanks to Data Science bootcamp, Louise will know on what not to do. 

Theater Outcomes vs Launch

For the 'Theater Outcomes vs Launch' diagram, we can draw two patterns. First, we can see from Theater outcomes over time is that Louise will know that summer time is the optimal range for her to host another play, with May being the best month of the year. Another pattern is that it appears winter time is the worst season to host her play(s) as we can visually see the number of successful theater kickstarters is at its trough.

Limitations and future planning

However, it's important to understand that simply following these trends does not gurantee success. Louise can make another play in Great Britian asking for ~$5000 in May, yet her play can stil fail. That's because our data set is limited to the amount of money asked (goal) & the time of the year. Our data set fails to account for other factors that could have cause the unsuccessful 'plays' to fail, such as the topic of the plays or perhaps even the locations. If someone hosted their play in a middle of no-where town or their play is about watching paint dry, how can anyone expect the play to succeed? It's important to consider that the trends are only there to give guidance. Therefore, it's important to gather additional data on her audience & present it in a visual way for ease of understanding. A bar graph would be a useful visualization of what topics her potential audience would be interested in. Another graph would be how her audience commutes so she can pick a location that's feasible, which can be determined through another bar graph or a pie chart. The more data Louise collects, the more educated she is to make a decision as she has a bigger picture in mind.
