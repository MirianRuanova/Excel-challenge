# Excel-challenge

## Conclusions from the provided data on crowdfunding campaigns:

1. Theater, Video/Film, and Music are the most popular categories for crowdfunding campaigns, and Theater campaigns have the highest success rate among them. Worldwide plays have shown to be the most successful within the Theater category. In the US there were 273 theater campains which 149 were successful versus 123 campaigns that were cancelled, failed.

2. The success rate varies among different categories, and Theater campaigns have a higher likelihood of success compared to Video/Film and Music campaigns. However, the reasons for this difference in success rates are not evident from the data alone.

3. In PT- Date Created Conversion we can see the number of campaigns that success or fail for the selected year or years and analyzed it by month. So for example, in 2018 was a good year for the theater campaigns, especially September was the month with the highest number of successful campaigns.

4. The campaigns with goals settled among 15000-24999 and 30000-34999 have reached the 100% of success. Those campaigns with goals greater than or equal to 50000 have been cancelled in a 9%, failed in a 53% and succeeded in a 37%. 

## Limitations of this dataset:

1. Small Sample Size: The dataset only includes 1,000 sample projects, which might not be representative of the entire crowdfunding landscape. A larger dataset would provide more reliable insights.

2. Lack of Audience Data: The dataset does not provide any information about the audience demographics or interests. Understanding the audience preferences and behavior is crucial in predicting campaign success and tailoring campaigns to specific target groups.

3. Limited Insight into Success Factors: While we can see which categories have higher success rates, the dataset does not provide insights into the specific factors that contribute to a successful campaign, such as marketing strategies, the project's uniqueness, or the project creator's reputation.

## Possible additional tables and/or graphs to create for additional value:

1. Backer Engagement Analysis: Create a table or graph showing the average donation amount per backer for each category. This would help identify which categories attract more generous backers and potentially indicate the perceived value of the projects.

2. Time to Success/Failure: Analyze the time it takes for campaigns in each category to reach their funding goal (or fail to do so) from the date they were created to the date they were launched. This can provide insights into the average duration of successful and unsuccessful campaigns.

3. Project Cancellation Analysis: Create a graph showing the reasons for campaign cancellations and compare them across categories. Understanding the reasons behind cancellations can help project creators avoid common pitfalls.



By analyzing these additional tables and graphs, we can gain a more comprehensive understanding of crowdfunding trends and success factors, helping both creators and investors make informed decisions in their campaigns.

## Statistical Analysis

To determine whether the mean or the median better summarizes the data for both successful and unsuccessful campaigns, we can compare their respective values and consider the distribution of the data.

#### Mean vs. Median for Successful Campaigns:

- Mean: 851.14 backers

- Median: 201 backers

#### Mean vs. Median for Unsuccessful Campaigns:

- Mean: 585.61 backers

- Median: 114.5 backers

#### Now let's consider the variability in each case:

- Variability for Successful Campaigns:

    - Standard Deviation: 1266.24

- Variability for Unsuccessful Campaigns:

    - Standard Deviation: 959.98


Observations:

For Successful Campaigns:

- The mean (851.14) is substantially higher than the median (201), indicating a right-skewed distribution.

- The standard deviation (1266.24) is relatively large, suggesting a wide spread of data points.

For Unsuccessful Campaigns:

- The mean (585.61) is also higher than the median (114.5), suggesting a right-skewed distribution.

- The standard deviation (959.98) is relatively large, indicating a considerable spread of data points.

Conclusion:

In both cases, the mean is higher than the median, indicating right-skewed distributions influenced by potential outliers with high backers' counts. However, since the mean is more affected by outliers, and the data appears to have some variability, the median might be a better measure to summarize the data for both successful and unsuccessful campaigns.

Overall, the choice between mean and median and the assessment of variability should consider the characteristics of the data distribution and the presence of outliers. In this case, the median might be a more robust measure, and successful campaigns exhibit higher variability in the number of backers compared to unsuccessful campaigns.