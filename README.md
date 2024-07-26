**Introduction**
---
# tiktok
Build ML model to classify user interaction data as a claim or opinion

**Findings**
--
- There are 19382 total, with 50% of claims - 9608.
- Engagement level strongly correlates with claim status, but we need to get more information.
- The overall authors' status with the claim video has a higher engagement level than those with the opinion video. In the claimed video, the banned author has significantly higher engagement than the active author.

In the current stage findings, the banned author with the claim videos has the highest engagement level. 

**Question**
--
1. How do the claims and opinion video data compare or differ? Consider views, comments, likes, and shares.

    From previous findings, we know that videos by banned authors tend to have more views, likes, and shares than videos by active and under-review authors. However, this only occurs in claim status, which means the engagement rates are more related to claim_status rather than the author_ban_status.

    - Also, we know that the claimed video has a higher view rate than the opinion video. We see that the mean and median of likes in claim video are overall higher than opinion video, this tells us that users are more likely to receive claim rather than opinion. Users are also willing to comment and share in claim videos as well. 

    - Authors have more comments, likes, and shares in opinion videos under review. We can make assumptions:
        - The opinions are controversial but still do not violate the rules.
