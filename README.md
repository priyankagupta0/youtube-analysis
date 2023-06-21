# Exploratory Data Analysing Using Youtube Video Data from My Favourite YouTube Channels
## 1. Aims, objectives and background
### 1.1. Introduction

Founded in 2005, Youtube has grown to become the second-largest search engine in the world (behind Google) that processes more than 3 billion searches per month [[1]](https://www.mushroomnetworks.com/infographics/youtube---the-2nd-largest-search-engine-infographic/). In fact, YouTube has one of the largest scale and most sophisticated industrial recommendation systems in existence [2](https://dl.acm.org/doi/10.1145/2959100.2959190). For new content creators, it is a challenge to understand why a video gets video and others do not. There are many "myths" about the success of a Youtube video [3](https://vidiq.com/blog/post/5-youtube-algorithm-myths-youtubers-need-to-know-about/), for example, if the video has more likes or comments, or if the video is of a certain duration. It is also worth experimenting and looking for "trends" in the topics that Youtube channels cover in a certain niche.

Having recently stepped into the content creation world with a new Youtube channel on data analytics and data science, I gained some insights on this topic which might be helpful for other new content creators. The scope of this small project is limited to my favourite channels and I will not consider other niches (that might have different characteristics and audience base). Therefore, this project will explore the statistics of my top 10 favourite Youtube channels.


### 1.2. Project Aims and Objectives
The main objectives of this project are to:

1. Familiarize myself with the Youtube API and learn how to retrieve video data.
2. Analyze the video data to investigate common assumptions or "myths" about video performance on Youtube, such as:
   - Examining the relationship between the number of likes and comments and the views a video receives.
   - Assessing whether video duration has an impact on views and user interaction (likes/comments).
   - Investigating the influence of title length on video views.
   - Analyzing the number of tags used in successful videos and identifying common tags among them.
   - Examining the upload frequency of creators and identifying the most popular days for video uploads.
3. Utilize Natural Language Processing (NLP) techniques to explore trending topics:
   - Identifying and visualizing the popular topics covered in the videos, potentially using word clouds to highlight significant terms.


### 1.3. Project Steps
The project will proceed through the following steps:

  1. Obtain video metadata from the Youtube API for the selected 10 channels. This involves creating a developer key, making API requests, and transforming the obtained responses into a format suitable for analysis.

  2. Preprocess the data and engineer additional features as needed. This may include cleaning and formatting the data, extracting relevant information, and creating new variables that can enhance the analysis.

  3. Perform exploratory data analysis on the collected video data. This step involves examining various aspects such as the relationship between likes/comments and views, the impact of video duration on user interaction, the influence of title length on views, the usage of tags in successful videos, and the upload frequency of creators.

  4. Draw conclusions based on the analysis conducted. This includes summarizing the findings and insights gained from exploring the data. The conclusions will aim to address the project objectives and shed light on the factors that contribute to video success on Youtube in the data science niche.

By following these steps, the project aims to provide valuable insights and understanding of the factors influencing video performance on Youtube within the data science niche.
