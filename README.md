# Main-Flow-Task-4

# Table of Contents
 Introduction
 Dataset
 Analysis
 Visualizations
 Correlation Analysis
 Conclusion

# Introduction
This project aims to analyze YouTube video data from the United States. The analysis includes data cleaning, visualization, and correlation analysis to gain insights into YouTube video trends.

# Dataset
The dataset used for this analysis is the USvideos.csv file, which contains information about YouTube videos in the United States.

# Analysis
The analysis includes the following steps:

Data Cleaning: 
# The dataset is cleaned by removing duplicates and unnecessary columns.
Data Transformation:
The publish_time column is converted to datetime format, and new columns are created for publish_month, publish_day, and publish_hour.
Category Mapping:
The category_id column is mapped to category names.
Yearly Analysis:
The number of videos published per year is calculated, and the total views per year are summed.

# Visualizations
The following visualizations are created to illustrate the findings:

Total Publish Video Per Year:
A bar chart showing the number of videos published per year.

Total Views Per Year: 
A bar chart showing the total views per year.

Top 5 Categories:
A bar chart showing the top 5 categories by total views.

Video Count by Category:
A count plot showing the number of videos in each category.

Number of Videos Published per Hour:
A bar plot showing the number of videos published per hour.

Videos Published Over Time:
A line plot showing the number of videos published over time.

Views vs Likes:
A scatter plot showing the relationship between views and likes.

Comments Disabled, Ratings Disabled, and Video Error or Removed: 
Count plots showing the number of videos with comments disabled, ratings disabled, and video error or removed.

# Correlation Analysis
The correlation between views and likes is calculated using the corr function.

# Conclusion
This analysis provides insights into YouTube video trends in the United States. The visualizations illustrate the findings, and the correlation analysis shows the relationship between views and likes.

# Linkedin Link: 
