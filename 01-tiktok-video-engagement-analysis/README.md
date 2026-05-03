# Exploratory-Data-Analysis-of-TikTok-Videos-Engagement-Content-Patterns-and-Moderation-Insights

## Overview
This project presents an exploratory data analysis (EDA) of a TikTok dataset to better understand video performance, user engagement, content categories, and moderation-related patterns. The analysis focuses on key metrics such as views, likes, comments, shares, downloads, video duration, claim status, verification status, and author ban status.

The goal is to extract meaningful insights from the data and highlight patterns that can support content analysis, platform understanding, and future machine learning applications.

## Objectives
- Explore the distribution of TikTok video engagement metrics
- Analyze relationships between views, likes, comments, shares, and downloads
- Compare claim and opinion content
- Investigate the impact of verification status and author ban status
- Identify moderation-related and engagement-related trends through data visualization

## Dataset Features
The dataset includes the following variables:
- `claim_status`
- `video_id`
- `video_duration_sec`
- `video_transcription_text`
- `verified_status`
- `author_ban_status`
- `video_view_count`
- `video_like_count`
- `video_share_count`
- `video_download_count`
- `video_comment_count`

## Tools and Libraries
This project was developed using:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Highlights
Some key findings from the analysis include:
- Video duration is relatively well distributed across short-form content ranges
- Engagement variables such as likes, comments, shares, and downloads are strongly right-skewed
- Most videos come from non-verified accounts
- Claim-related content appears more associated with review or ban actions than opinion content
- Videos linked to under-review or banned authors tend to have much higher median view counts
- A positive relationship exists between views and likes for both claim and opinion videos

