YouTube Voice Over Link - https://youtu.be/jiBfI1jX1pI

# Video Claims Analysis and Visualization

This project focuses on analyzing and visualizing data related to video claims, including their status, view counts, likes, shares, and more. The dataset provides a rich set of attributes that describe each video and its interaction metrics, allowing for insightful analysis of video performance and claim verification.

## Dataset Description

link for Dataset on kaggle - https://www.kaggle.com/datasets/raminhuseyn/dataset-from-tiktok


The dataset consists of **19,382 rows** and **12 columns** with the following attributes:

- `#`: Unique identifier for each row.
- `claim_status`: The status of the claim (e.g., "claim", "opinion"). This column has some missing values.
- `video_id`: Unique identifier for each video.
- `video_duration_sec`: Duration of the video in seconds.
- `video_transcription_text`: The transcribed text of the video content, with some missing values.
- `verified_status`: Indicates whether the claim has been verified (e.g., "verified", "not verified").
- `author_ban_status`: Status of the author's account (e.g., "active", "under review", "banned").
- `video_view_count`: The number of views the video has received, with some missing values.
- `video_like_count`: Count of likes the video has received, with some missing values.
- `video_share_count`: Count of shares the video has received, with some missing values.
- `video_download_count`: Count of downloads for the video, with some missing values.
- `video_comment_count`: Count of comments on the video, with some missing values.

## Installation

To get started, set up your Python environment with the necessary libraries for data manipulation and visualization. You can install them using `pip`:

```bash
pip install pandas plotly


