# Tiktok
**Introduction**
--
Build ML model to classify video content as a claim or opinion to enhance the moderating process and reduce the backlog of user reports. 

**Findings**
--
- There are 19382 total, with 50% of claims - 9608.
- Engagement level strongly correlates with claim status, but we need to get more information.
- The overall authors' status with the claim video has a higher engagement level than those with the opinion video. In the claimed video, the banned author has significantly higher engagement than the active author.

In the current stage findings, the banned author with the claim videos has the highest engagement level. 

**Key Statistical Findings**
--

1. Difference in Video View Counts Between Verified and Unverified Accounts

- Conducted a t-test to compare mean video views between verified and unverified accounts.

- Result: 

The p-value was less than the significance level of 5%, leading to the rejection of the null hypothesis.

- Conclusion: 

There is a statistically significant difference in the mean video views between verified and unverified accounts, with unverified accounts having higher engagement on average.

2. Engagement Level by Claim Status

- Engagement level strongly correlates with claim status. Claim videos generally have higher engagement than opinion videos.

- Observation: 

Banned authors' claim videos have significantly higher engagement compared to those from active authors.

3. Claim vs. Opinion Videos

- Claim videos tend to have more views, likes, and shares than opinion videos. The median and mean for likes are also higher for claim videos, suggesting users are more inclined to interact with claim-based content.

**Question**
--
1. How do the claims and opinion video data compare or differ? Consider views, comments, likes, and shares.

    From previous findings, we know that videos by banned authors tend to have more views, likes, and shares than videos by active and under-review authors. However, this only occurs in claim status, which means the engagement rates are more related to claim_status rather than the author_ban_status.

    - Also, we know that the claimed video has a higher view rate than the opinion video. We see that the mean and median of likes in claim video are overall higher than opinion video, this tells us that users are more likely to receive claim rather than opinion. Users are also willing to comment and share in claim videos as well. 

    - Authors have more comments, likes, and shares in opinion videos under review. We can make assumptions:
        - The opinions are controversial but still do not violate the rules.

2. Are there statistical differences between verified and unverified accounts in terms of the mean video view counts?
- After conducting the t-test, the p-value is less than the significance level of 5%, leading to the rejection of the null hypothesis. This brings us to the statistically significant difference in the mean video views between verified and unverified accounts on TikTok.
