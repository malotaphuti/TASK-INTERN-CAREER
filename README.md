This document outlines the process and methodologies used to analyze a dataset of YouTube streamers. The primary goal of this analysis is to understand key metrics and trends among top YouTube content creators. This includes investigating subscriber counts, visit counts, likes, comments, and identifying top-performing countries and categories.

Data Overview
Dataset Description
The dataset (youtubers_df.csv) contains the following attributes:

Rank: The rank of the YouTube channel.
Username: The username of the YouTube channel.
Categories: The content category of the YouTube channel.
Suscribers: The number of subscribers for the channel.
Country: The country of origin of the YouTube channel.
Visits: The number of visits to the channel.
Likes: The number of likes received by the channel.
Comments: The number of comments on the channel's videos.
Data Preparation
Loading Data: The dataset was loaded into a Pandas DataFrame for analysis.
Data Cleaning: This included handling missing values, correcting any misspellings in column names, and converting data types where necessary.
Exploratory Data Analysis (EDA): Initial exploration to understand the structure and summary statistics of the data.
Key Analyses
General Overview
Summary Statistics: Calculated descriptive statistics such as mean, median, and standard deviation for numerical columns like subscribers, visits, likes, and comments.
Data Types: Checked and confirmed the data types of each column.
Missing Data and Outliers
Missing Values: Identified missing data points in the dataset and employed strategies like imputation or removal based on the context.
Outliers: Detected outliers in numerical columns using visual and statistical methods and handled them appropriately.
Subscriber Analysis
Top Channels: Identified the top 5 channels with the highest number of subscribers.
Category Analysis: Analyzed which categories have the most subscribers overall.
Country Analysis: Found the country with the highest number of subscribers and listed the top 10 countries by subscriber count.
Engagement Analysis
Correlation Study: Examined the correlation between comments, likes, and visits to understand the relationships between these engagement metrics.
Popular Content: Identified the most liked and commented categories and channels.
Audience Analysis
Regional Preferences: Investigated regional preferences by analyzing the distribution of audiences across different countries and content categories.
Top Categories by Country: Determined the most popular categories in each country based on the number of subscribers.
Visualization
Bar Charts and Scatter Plots: Used bar charts to display the top categories and countries by subscribers, and scatter plots to visualize relationships between engagement metrics like comments and likes.
Correlation Heatmaps: Created heatmaps to display correlations between different numerical variables in the dataset.
Conclusion
The analysis provided insights into the distribution and popularity of YouTube channels across different regions and content categories. It highlighted the engagement levels through likes, comments, and visits, and identified key trends among top-performing YouTube streamers. These findings can help inform content creators and marketers about popular trends and audience preferences on YouTube.
