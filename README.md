# Sidemen-Youtube-API

# YouTube Data Analysis

## Overview

This Python script utilizes the YouTube Data API to fetch and analyze data related to a specific YouTube channel (in this case, the 'Sidemen' channel). The script covers the following functionalities:

1. **Fetching Channel Statistics:**
   - Utilizes the YouTube API to retrieve statistics such as the number of subscribers, total views, total videos, and the ID of the upload playlist.

2. **Fetching Video Information:**
   - Retrieves video IDs from the upload playlist.
   - Gathers detailed information for each video, including title, description, tags, publication date, view count, like count, and more.

3. **Data Pre-processing:**
   - Handles missing values and data types.
   - Converts time-related columns to appropriate formats.
   - Extracts additional features like the day of the week and tag count.

4. **Exploratory Data Analysis (EDA):**
   - Identifies the best-performing videos based on view count.
   - Visualizes the distribution of views per video and explores the relationship between views, likes, and comments.
   - Examines the distribution of video durations.
   - Creates a word cloud for video titles, highlighting frequently used words.

## Getting Started

### Prerequisites
- Ensure you have the required Python packages installed (`google-api-python-client`, `pandas`, `matplotlib`, `seaborn`, `nltk`, `wordcloud`, `isodate`).
- Obtain a valid API key from the [Google Cloud Console](https://console.cloud.google.com/) and replace the placeholder `api_key` in the script.

### Running the Script
1. Copy the script into your Python environment.
2. Run each code cell sequentially.

## Notes

- This script is specific to the 'Sidemen' YouTube channel and may need adjustments for other channels.
- The API key is a sensitive credential; avoid sharing it publicly.
- Ensure compliance with the [YouTube API terms of service](https://developers.google.com/youtube/terms/api-services-terms).

## Acknowledgments

- [Google API Client Library Documentation](https://developers.google.com/youtube/v3)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [NLTK Documentation](https://www.nltk.org/)
- [WordCloud Documentation](https://github.com/amueller/word_cloud)


