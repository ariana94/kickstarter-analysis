# Kickstarting with Excel
---
## Overview of Project

This project reviews data on several thousand crowdfunding projects through Kickstarter. I have performed a data analysis
with the accumulated information in order to track trends on campaign types in various countries. With this data I was able
to make correlations with the months the campaigns were started, goal vs pledged amounts, and category/sub category.

### Purpose

The overall purpose of this project was to help Louise gather all the information she needed to run a campaign with a high
chance of success.

---

## Analysis and Challenges
Starting with this massive amount of data seemed intimidating at first glance. My first step was to break down some of the larger 
data by adding a 'percentag funded' and 'average donation' column to help futher organize and then color code the data. Once that 
was complete I converted the Unix timestamps into readable data and broke the combined category column down into parent category
and sub category.
![Parent Category Outcomes chart](https://user-images.githubusercontent.com/19378130/170583170-572945b4-89cf-4a99-a7d9-47c4816208f5.png)

Once the data was refined, I was able to form pivot tables and charts to start looking at outcomes.

### Analysis of Outcomes Based on Launch Date

![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/19378130/170583415-aa274271-b8da-47f8-9347-699b99450c07.png)

With this line chart, we can see that May, June, and July are the most successful months to launch a campaign.

![Theater_outcomes_vs_launch](https://user-images.githubusercontent.com/19378130/170583878-2e9d8d2d-0258-477e-a105-b6029bbfada2.png)

If we futher break it down by looking at just the Theater category, it still supports similar data favoring May-July.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/19378130/170584521-3ea42a5e-085d-4b0d-afa5-1bf7e3565011.png)

In the Plays category, we can see that the most successful goals were under $5,000. Between the Less than 1000 (76%/24%) and the 1000 to 4999 (73%/27%) range was around a 73% success to 27% failure rate.

### Challenges and Difficulties Encountered
Personally, my lack of experience in Excel made things a bit tricky at first. I spent a lot of time playing around with formulas and charts
and failing to get the results I wanted. After some trial and error I was able to get the hang of things. Memorizing the formulas is a bit
tricky. It is helpful that Excel is very simple in its formula names and has a great function syntax to help guide me along.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

We are able to see that the most successful month for launching a campaign is May, followed by June and July. These launch
dates yielded a higher percentage of successful vs failed campaigns.

![percent by launch date](https://user-images.githubusercontent.com/19378130/170589523-6c146aea-1ba2-48c3-936e-cecd35bf1466.png)

Out of the total number of launched play campaigns, 65% end up being successful, 8.72% are in May, 7.79% in June, and 7.04% in
July. Additionally, although not as successful, the lowest rates of failure are Jan with 1.88% (Success 4.03%), and Mar (Success 4.32%) 
and Nov (Success 4.41%) with 1.97% each.

- What can you conclude about the Outcomes based on Goals?

Plays with a goal above 5000 and under 25000 only have about a 50% chance of success. The most success was seen at 4999 and lower.


- What are some limitations of this dataset?

This data is only from 2009 to 2017, so it may not be as accurate in 2022. We also can't see how these individual campaigns
were marketed to raise funds. It is possible that campaigns with more marketing had a higher success rate, but this data set
does not include that information.


- What are some other possible tables and/or graphs that we could create?

We could create a table or graph to see if there is a correlation with key words in the name and average donation. I personally would
like to know if the campaigns with the sillier names were able to get more per a donation. It would also be niffty to see if the backer
count affects the rate of success.
