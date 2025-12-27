# YouTube-Trending-Videos-Analysis
This project explores what makes videos trend on YouTube by analyzing historical trending data.
The goal is to uncover patterns related to content categories, creator dominance, engagement quality, and publishing time, and convert them into actionable insights.

Rather than focusing only on raw popularity (views), this analysis emphasizes engagement ratios and temporal behavior, which provide a more realistic picture of audience interaction.

# Dataset Overview
Source: YouTube Trending Videos dataset from Kaggle: https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset
Region: United States
Data includes:
Video metadata (title, channel, category)
Publish timestamps
View, like, and comment counts
Trending dates
Each row represents a video that appeared on YouTube’s trending list.

# Tools Used
Python
Pandas – data cleaning and aggregation
Matplotlib – visualizations
NumPy – numerical operations
Jupyter Notebook – analysis workflow

# Key Analysis Performed
  1. Category & Channel Analysis
      Identified categories that dominate trending by volume
      Analyzed which channels appear most frequently on the trending list

  2. Engagement Analysis
      Created like ratio and comment ratio metrics to normalize engagement
      Compared engagement quality across categories
      Distinguished between passive (likes) and active (comments) interaction

  3. Distribution Analysis
      Studied view count distribution using log-scale transformation
      Identified long-tail behavior driven by viral outliers

  5. Time-Based Analysis

      Analyzed trending frequency by:
        Publish hour
        Day of the week
        Weekday vs weekend
      Studied how engagement varies with publish timing

# Key Findings
Entertainment, Gaming, and Music dominate trending by volume.
Education and How-to & Style videos show stronger engagement per view, despite trending less often.
Trending visibility is highly concentrated among a small number of established channels.
View counts follow a right-skewed (long-tail) distribution, where a few viral videos account for massive reach.
Late afternoon to early evening (~3 PM – 6 PM) is the most common publish window for trending videos.
Friday shows the highest trending activity among weekdays.
Engagement quality varies less by time than trending frequency, indicating that timing affects visibility more than interaction depth.

# Limitations
The dataset includes only trending videos, not the full YouTube population.
Findings are descriptive, not causal.
Engagement ratios may be affected by disabled likes/comments or low-view edge cases.
Results are specific to a region and time period.
