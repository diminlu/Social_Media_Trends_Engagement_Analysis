# Social_Media_Trends_Engagement_Analysis
An analytics project covering 1,000 posts across five platforms and five content formats, built into three interactive dashboards that track engagement, reach, and posting performance from January 2024 through December 2025.\

**Executive Summary**

This project analyzes two years of social media posting data to identify which platforms, content formats, and combinations of the two drive the strongest engagement. The dataset covers 1,000 posts across Facebook, Instagram, LinkedIn, TikTok, and Twitter, spanning five content types: Carousel, Image, Reel, Text, and Video.\
The analysis was built into three dashboards: a Platform & Content Performance Dashboard, an Engagement Trend Dashboard, and a Top Performers & Outliers Dashboard. Across all three, one finding stands out clearly: TikTok, and specifically TikTok's Video and Reel content, accounts for a disproportionate share of the account's top engagement results.\

**Introduction**

<img width="2002" height="1095" alt="image" src="https://github.com/user-attachments/assets/07a3b4ec-1cd3-47a2-8142-9efdbb7da1ef" />
<img width="2002" height="1095" alt="image" src="https://github.com/user-attachments/assets/1fce032f-9390-401b-8335-0e332fe63a6c" />
<img width="2002" height="1095" alt="image" src="https://github.com/user-attachments/assets/4cb4350b-ef78-4892-92ee-0ddc35218e9d" />

This project was built to answer a specific set of questions about social media performance: which platforms and content types perform best, how performance moves over time, and which individual posts and patterns are worth studying more closely. The source data includes impressions, reach, likes, comments, shares, and engagement rate for each post, along with platform, content type, and post date.\
The three dashboards were designed to be filtered by platform, content type, and year using shared slicers, so a stakeholder can isolate any combination and see performance recalculate across every chart at once.\

**Business Problem**

Social media teams managing multiple platforms and content formats often face a common set of challenges:
1.	Identifying which platform delivers the strongest return on posting effort.
2.	Determining which content formats consistently outperform others.
3.	Understanding whether platform and content type interact, rather than performing independently.
4.	Tracking whether engagement is improving, declining, or holding steady over time.
5.	Distinguishing genuinely high-performing posts from posts that simply reached a large audience.
6.	Identifying posts with unusually weak reach relative to impressions, which may signal a distribution issue.

**Project Objectives**

•	Compare platform performance on impressions, reach, and engagement rate.
•	Compare content type performance on the same measures.
•	Identify the strongest platform and content type combinations.
•	Break down engagement composition (likes, comments, shares) by platform.
•	Track engagement rate over 24 months to identify trend or seasonality.
•	Identify the top and bottom performing individual posts and what they have in common.
•	Examine the relationship between share count and engagement rate.
•	Identify posts where reach fell well short of what impressions would predict.

**Stakeholders**

1.	Social Media Managers
2.	Content Strategy Teams
3.	Marketing Leadership
4.	Brand and Creative Teams
5.	Analytics and Reporting Teams

**Success Criteria**

1.	Social Media Managers
2.	Content Strategy Teams
3.	Marketing Leadership
4.	Brand and Creative Teams
5.	Analytics and Reporting Teams

**Data Preparation**

Data Cleaning\
•	Verification of post-level uniqueness (no duplicate Post IDs).
•	Validation of Impressions, Reach, Likes, Comments, and Shares as non-negative integers.
•	Standardization of Platform and Content Type category labels.
•	Confirmation that Reach never exceeds Impressions for any post.
Data Transformation\
•	Grouping of Post Date into Month and Year for trend analysis.
•	Calculation of Reach Rate (Reach divided by Impressions) at the post level.
•	Aggregation of engagement rate by platform, content type, and platform-content pairing.
•	Calculation of engagement composition (likes, comments, shares as a share of total engagement) by platform.

**KPI Calculations**

Key performance indicators calculated for the dashboards included:\
•	Total Posts
•	Average Engagement Rate %
•	Average Reach Rate
•	Average Impressions by Platform and Content Type
•	Engagement Composition (Likes / Comments / Shares share)
•	Monthly Average Engagement Rate
•	Top 10 and Bottom 10 Posts by Engagement Rate

**Dashboard Development**

Dashboard 1: Platform & Content Performance Dashboard\
This dashboard compares platforms and content types side by side, and identifies which specific combinations perform best.\
Key Metrics\
•	Total Posts
•	Average Engagement Rate %
•	Average Reach Rate
Visualizations\
•	Average Impressions by Platform, with Engagement Rate % overlay
•	Average Impressions by Content Type, with Engagement Rate % overlay
•	Average Engagement Rate % by Platform and Content Type
•	Engagement Mix (Likes / Comments / Shares) by Platform
Business Purpose\
Gives content and platform teams a single view for deciding where to invest posting effort, and which platform-content pairings are worth repeating.\
Dashboard 2: Engagement Trend Dashboard\
This dashboard tracks how engagement rate has moved over the two-year period covered by the data.\
Key Metrics\
•	Average Engagement Rate %
•	Best Performing Month
•	Worst Performing Month
Visualizations\
•	Average Engagement Rate % by Month
•	Engagement Rate %: 2024 vs. 2025 by Month
Business Purpose\
Shows whether engagement is trending, seasonal, or stable, so posting strategy is based on an actual pattern rather than assumption.\
Dashboard 3: Top Performers & Outliers Dashboard\
This dashboard isolates individual posts, rather than platform or content type averages, to identify what the best and worst performing posts have in common.\
Key Metrics\
•	Total Posts
•	Top Post Platform
•	Top Post Content Type
Visualizations\
•	Top 10 Posts by Engagement Rate %
•	Bottom 10 Posts by Engagement Rate %
•	Shares vs. Engagement Rate % (scatter)
•	Impressions vs. Reach (scatter, with trendline)
Business Purpose\
Helps content teams study specific high-performing posts directly, and flags posts with unusually weak reach that may be worth investigating for distribution issues.\

**Key Findings**

Platform Insights\
•	TikTok leads on both average impressions (233,931) and average engagement rate (12.26%), more than double every other platform.
•	Instagram is the next-strongest platform on engagement rate, at 6.46%, followed by LinkedIn (6.05%) and Facebook (5.78%).
•	Twitter has the weakest average engagement rate of the five platforms, at 3.31%.
Content Type Insights\
•	Reel is the strongest content type overall, averaging 10.30% engagement, followed by Video at 7.96%.
•	Carousel, Image, and Text all average under 6% engagement, regardless of platform.
•	TikTok Video (12.31%) and TikTok Reel (12.23%) are the two strongest platform-content combinations in the dataset, well ahead of the next-best pairing, Instagram Video, at 6.64%.
Engagement Composition Insights\
•	Likes account for 62.6% of total engagement across the dataset, followed by Shares (22.8%) and Comments (14.6%).
•	Instagram is the most Likes-heavy platform, at 78% of its engagement.
•	LinkedIn generates the highest share of Comments (24.7%); Twitter and Facebook generate the highest share of Shares (34.6% and 30.6%).
Trend Insights\
•	Engagement rate stayed within a fairly narrow range across the 24-month period, roughly 6.3% to 8.7%, with no clear seasonal pattern.
•	February 2024 was the strongest month on record (8.65%); December 2025 was the weakest (6.29%).
Top Performer Insights\
•	All ten of the top-performing individual posts by engagement rate are TikTok posts, seven Reels and three Videos.
•	Engagement rate rises sharply with share count up to roughly 2,000 shares, then levels off.
•	Impressions and reach are closely correlated for most posts, with a small number of posts falling well below the expected reach for their impression count.

**Business Recommendations**

1.	Prioritize TikTok as the primary platform for new content investment and testing.
2.	Shift overall content mix toward Reel and Video, and reduce reliance on Image and Text formats.
3.	Treat TikTok's advantage as specific to its Video and Reel content, not as evidence that video performs the same way on every platform.
4.	Design more comment-generating content (questions, polls) outside of LinkedIn, where comment engagement already performs well.
5.	Study what drives LinkedIn's comment-heavy engagement and Twitter and Facebook's share-heavy engagement, and apply those lessons across platforms.
6.	Focus planning on content format rather than seasonal timing, given the lack of a clear seasonal pattern.
7.	Use share count as an early performance signal rather than a target to keep pushing past roughly 2,000 shares.
8.	Investigate the specific posts with reach well below their expected level, to check for distribution or algorithm issues.
9.	Reduce production investment in Text and Image content, unless a specific platform shows an exception.
10.	Review the dashboards on a monthly basis to catch any future shift away from the current stable trend.

**Conclusion**

1.	Prioritize TikTok as the primary platform for new content investment and testing.
2.	Shift overall content mix toward Reel and Video, and reduce reliance on Image and Text formats.
3.	Treat TikTok's advantage as specific to its Video and Reel content, not as evidence that video performs the same way on every platform.
4.	Design more comment-generating content (questions, polls) outside of LinkedIn, where comment engagement already performs well.
5.	Study what drives LinkedIn's comment-heavy engagement and Twitter and Facebook's share-heavy engagement, and apply those lessons across platforms.
6.	Focus planning on content format rather than seasonal timing, given the lack of a clear seasonal pattern.
7.	Use share count as an early performance signal rather than a target to keep pushing past roughly 2,000 shares.
8.	Investigate the specific posts with reach well below their expected level, to check for distribution or algorithm issues.
9.	Reduce production investment in Text and Image content, unless a specific platform shows an exception.
10.	Review the dashboards on a monthly basis to catch any future shift away from the current stable trend.
