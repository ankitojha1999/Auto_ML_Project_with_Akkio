# Auto_ML_Project_with_Akkio


Overview
This project involves analyzing and visualizing data related to video claims, including their status, view counts, likes, shares, and more. The dataset contains various attributes that describe each video and its interaction metrics, allowing for insightful analysis of video performance and claim verification.

Dataset Description
The dataset consists of 19,382 rows and 12 columns with the following attributes:

#: Unique identifier for each row.
claim_status: The status of the claim (e.g., "claim", "opinion"). This column has some missing values.
video_id: Unique identifier for each video.
video_duration_sec: Duration of the video in seconds.
video_transcription_text: The transcribed text of the video's content, with some missing values.
verified_status: Indicates whether the claim has been verified or not (e.g., "verified", "not verified").
author_ban_status: Status of the author's account (e.g., "active", "under review", "banned").
video_view_count: The number of views the video has received, with some missing values.
video_like_count: Count of likes the video has received, with some missing values.
video_share_count: Count of shares for the video, with some missing values.
video_download_count: Count of downloads for the video, with some missing values.
video_comment_count: Count of comments on the video, with some missing values.
Installation
To get started with this project, ensure you have the necessary Python environment set up. You may need libraries such as pandas, plotly, and others for data manipulation and visualization.

pip install pandas plotly
Usage
You can run analyses on the dataset to extract meaningful insights. The following analyses can be performed:

Claim Status Analysis: Determine the distribution of claims and opinions.
Video Performance: Analyze metrics such as view counts, likes, shares, and comments.
Verification Status: Explore the relationship between claim verification and video engagement.
Example Analysis

You can perform visualizations using the plotly library to create various charts such as:

Bar charts to visualize the count of claims by status.
Scatter plots to analyze the relationship between likes and views.
Box plots to understand the distribution of video durations across different claim statuses.
Contributing
Contributions are welcome! If you have ideas for improvements or additional analyses, feel free to open an issue or submit a pull request.



Acknowledgements
Pandas Documentation
Plotly Documentation
