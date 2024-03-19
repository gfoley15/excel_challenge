# excel_challenge

# Crowdfunding analysis
## Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
- Theater had the most campaigns by category compared to any other categories as well as the highest number of successful campaigns with 187. Specifically, Plays, a sub-category of theater, had the most campaigns by sub-category too - far beyond the next closest sub-category of rock, a sub-category of music, at 49.
- Despite the campaign's Goal range, 73% of campaigns were successful on avergae. The best success rate occurred when the campaign's Goal was between 15000 to 19999, 20000 to 24999, or 30000 to 34999. In each of these Goal ranges, the success rate was 100%.
- Looking at all years (2010 to 2020), Campaigns launched in June and July were more successful (had a higher number of successful campaigns) than campaigns launched in any other month. This could be due to June and July being after school / during summer vacation when crowdfunding efforts were able to engage with to more people or attract a higher number of people to donate or pledge to their cause. Overall, this data point helps us understand the seasonality of campaigns.
- The U.S. had the highest number of campaigns when compared to the other countries in the dataset - Australia, Switzerland, Denmark, Canada, Great Britian, Italy, and China.

## What are some limitations of this dataset?
- Limited to timeframeof dataset. The data is only between 2010 to 2020. The prompt states that in the early 2000s, for which there is no data to analyze. There would also be valuable insights after 2020 due to the change in socioeconomic landscape as well as having the most up to date information to make infromed decisions.
- Limited data points about what the campaign's crowdfunding tactics for outreach. We're not able to determine if there is a best approach to advertisments, channel communications to attract an audience of backers to be successful.
- Currency differs between campaigns making it challenging to review financial impacts from a single monetoary number like USD. There could obviously be some additional data preparation to convert all currencies to a single currency like USD in order to allow for financial analysis about pledged vs. funded amounts, average donations.
- No demographic information about backers; having more information would allow us to analyze who is making donations, what age they are, where they live, what their income is. Also, would allow us to review campaign effectiveness across demographics and target audiences.

## What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
- Correlation grpah between funding goal, pledged amount and outcome
  - With a correlation graph between funding goal, pledged amount and outcome, we would be able to review the impact and trends of campaign funding on the outcome and determine if there is a threshold or target that could be identified for future campaigns. This could be a successful measurement and used to plan around.
- Campaign outcomes by country
  - This would have assisted with drawing conclusions about which location has the best success rate for crowdsourcing campaigns and parhaps where future crowdfunding campaigns should be held.
  - This could be represented in either a pie chart with total campaigns (country legend), a stacked bar chart with count of campaign outcome (country on x axis). 
- Category trends by year, by success rate, by average donation
  - This would assist with reviewing trends of successful campaigns over time to see which campaign cateogies are successful within the most recent years to better determine if a crowdfunding campaign may be a viable option to raise awareness and captial for the mission. If the crowdfunding efforts are unsuccessful within your category or domain, this information would enable alternative money raising efforts to be considered and implemented.
  - It would also assist with determining an estimated success rate and a target for average donation amount to be successful.
- Average donation by country, by year, by category
  - This would assist with drawing conclusions about expected average donations per location to be in order to track and gauge donations actively during a new campaign and take action to remediate low donation amounts.
  - Average doantions could also be reviewed year over year, month over month to analyze percent increase or decrease.
  - Average donations could also be reviewed by category to understand typical donation size per category.

# Determine whether the mean or the median better summarizes the data
- The median best summarizes the data since it is less impacted by the extreme numbers of backers that come to light when calculating the mode.
- In both successful and unsuccessful campaigns, the mean of backers is significantly higher than the median (851.15 vs 201, 585.62 vs 114.5, respectively). This is likely due to outliers / a high number of backers in a few campaigns, but does not best represent the central tendency of the dataset in which the majority number of backers is centered around the median (201 and 114.5)

# Determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?
- The variance of successful campaigns is higher than variance of unssuccessful campaigns. The variance calcualtion is higher for successful campaigns vs unsuccessful campaigns - 1603373.732 vs 921574.6817 respectively.
- There is more variability in the number of backers count for successful campaigns compared to unsuccessful campaigns.
- This makes sense as successful campaigns would vary more as the campaign grows, gains popularity, causing more backer to participate. Unsuccessful campaigns would likely stop sooner and reach less audience, therefore having less backers and less variance.

