# tds-project1
- This repository contains user and repository data obtained from GitHub's API, focusing on developers in Berlin with over 200 followers.
- Surprisingly, nearly 70% of the users from Berlin with over 200 followers actively contribute to repositories in at least three different programming languages, showcasing the versatility of developers in the region.
- Based on the analysis, developers should consider contributing to open-source projects to enhance their skills and visibility within the GitHub community.

## Analysis Process

1. **Data Collection**:
   - I utilized the GitHub API to extract user data specifically for developers located in Berlin with over 200 followers. This focused my analysis on a segment of the tech community.

2. **Data Cleaning**:
   - The raw data was cleaned using Pandas. I standardized company names by removing leading '@' symbols and converting them to uppercase. Null values were replaced with empty strings to maintain the dataset's integrity.

3. **Data Exploration**:
   - I performed EDA using Jupyter Notebook and Matplotlib to uncover trends and patterns. Key metrics, such as average followers and public repositories per user, were calculated and visualized through various charts for better insight.
