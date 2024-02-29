# ANOVA
_Article Performance Analysis_
*Overview*
This project explores the relationships between article performance metrics, author contributions, and reader reactions. The goal is to identify factors contributing to higher article engagement and performance on a content platform.

Datasets
The analysis utilizes three main datasets:

Article_Names_updated.csv: Contains article titles, visits, hits, time spent, and exit rates.
Authors_Name_updated.csv: Includes author details and potentially links to articles.
Reactions_updated.csv: Records reader reactions to articles.
A combined dataset was manually created to establish connections between articles, authors, and reactions, resulting in Article_Names_combined_updated.csv.

Methodology
The analysis involved the following steps:

Data Preparation: Conversion of exit rates to decimal format and parsing of datasets to correct structure.
Performance by Author: Calculation of average performance metrics (visits, hits, time spent, exit rate) per author.
Correlation Analysis: Examination of the relationship between article reactions and performance metrics using Pearson correlation coefficients.
Visualization: Creation of a heatmap to visualize the correlation between reactions and article performance metrics.
Key Findings
Articles with more reactions tend to have higher exit rates, suggesting that while they attract attention, they might not always encourage sustained engagement.
There is a moderate positive correlation between reactions and both article visits and hits, indicating that engaging content that prompts reactions also attracts more visitors and interactions.
The analysis of performance by author revealed that articles with unspecified authors have the highest average visits and significant time spent, suggesting the importance of content promotion and topic selection.
Visualization
A heatmap was used to visually represent the correlation between reactions and article performance metrics, highlighting the strength and direction of relationships through color intensity.

Conclusion
This analysis provided insights into how reader reactions correlate with article performance metrics. Understanding these relationships helps in strategizing content creation and promotion to enhance reader engagement and article success.
