**TikTok Video Content Classification**
--

Welcome to the TikTok Video Content Classification project! This repository contains the analysis and machine learning model development aimed at classifying TikTok video content as either a claim or an opinion. The goal is to enhance the moderation process and reduce the backlog of user reports by automating content classification.

**Project Background**
-

TikTok is a leading social media platform in the short-form video industry, operating since 2016 with a business model centered around user-generated content and advertising revenue. The primary objective is to improve content moderation efficiency to maintain community standards and enhance user experience.

**Key Business Metrics:**
-

- Total Videos Analyzed: 19,382

- Engagement Metrics: Views, Likes, Comments, Shares, Downloads

- Author Status: Verified, Unverified, Banned, Active, Under Review

**Data Structure and Initial Checks**
-

This dataset only contains one table, and the discription of this table is as follow:


[EDR diagram]


**Executive Summary**
-

**Overview of Findings**

The analysis reveals that claim videos receive significantly higher engagement compared to opinion videos, with unverified accounts generating more views on average than verified accounts. Additionally, the sum of videos from active authors exhibit exceptionally high engagement levels, particularly within the claim category. These insights suggest that engagement metrics are more closely related to the content type (claim vs. opinion) rather than the author's verification or ban status.

**Insights Deep Dive**
-

**1. Classification Accuracy**
- `Main Insight 1`: The model successfully classifies video with an accuracy of ~99%, effectively distinguishing between claims and opnions.

- `Main Insight 2`: The model achieved a precision of 100% and a recall of nearly 100% for claim videos, meaning all videos predicted as claims are actual claims, with almost all true claims correctly identified.

- `Main Insight 3`: The engagement metrics are solely related to the claim status of a video, instead of the author's status. 

[Diagram]

**2. Engagement Patterns by Content Type**
- `Main Insight 1`: The median number of views for claim videos is 501,555, which is significantly higher than the 4,953 median views for opinion videos. 

- `Main Insight 2`: The engagement level for claim videos are distributed along the x-axis, showing a larger variability and the presence of outliers, whereas opinion videos are mostly concentrated around the same engagement rate, reflecting a more consistent but lower level of interaction.

- `Main Insight 3`: Engagement levels are strongly correlated with claim status, regardless of the author's verification or ban status.

- `Main Insight 4`: Opinion videos under review receive more comments, likes, and shares, suggesting that while they are engaging, they do not violate community guidelines.

**3. Author Status Impact on Engagement**

- `Main Insight 1`: The average of banned authors' claim videos have the highest engagement levels, surpassing those of active and under-review authors.

- `Main Insight 2`: Verified accounts generally receive more consistent engagement, but unverified accounts outperform them in view counts.

- `Main Insight 3`: The discrepancy in engagement between banned and active authors highlights potential issues with content that leads to bans.

- `Main Insight 4`: Engagement patterns suggest that users are more drawn to content from banned authors, possibly due to controversial or high-impact content.
