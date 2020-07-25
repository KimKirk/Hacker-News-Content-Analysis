# Hacker-News-Content_Analysis
- Hacker News Content Analysis

- Technology: SEO Content Development

- Descriptive multivariate data analysis was conducted on Hacker News content. 20,000 Hacker News posts data set from Kaggle were imported, cleaned, and analyzed. Content analysis was conducted to identify which post types received the most comments and the top five hours in which to make comments, with the idea that Hacker News is extremely popular in technology circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors; thus, increase the profile of the subject matter in the posts.

- The data was analyzed and descriptive statistics were generated. Means were calculated for post types to identify which post type receives the most comments on average. Frequency counts per hour were calculated for comments to identify the top 5 hours in which to make comments.

- 20,000 posts data set from Kaggle that includes 7 features. A complete explanation can be found at the Kaggle webpage: https://www.kaggle.com/hacker-news/hacker-news-posts

## Processing Instructions:
- https://drive.google.com/file/d/1fQfqKCnHTR0HBUNsxNtnmwZU-gfcuraA/view?usp=sharing to view HMTL version of report.
- To improve reproducibility of the data analysis, a Jupyter Notebook file is included.

## Steps to Transformation:
- Data was downloaded from https://www.kaggle.com/hacker-news/hacker-news-posts
- File “hacker_news.csv” was imported into Jupyter Notebook.
- Removed headers.
- Converted values to lowercase.
- Converted Date/Time String to datetime objects.
- Formatted time objects.
- Identified post type that receives the most comments on average.
- Identified top five hours to make comments on posts.
