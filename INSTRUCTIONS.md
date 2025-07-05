# Welcome Group2 to your project phase

Data-Link: https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships/data

## The scenario: Social Media Addiction
You are now part of the Digital Wellness Institute (DWI), a leading non-profit organization dedicated to understanding the societal impacts of digital technologies and promoting healthy digital habits.
The DWI is launching a new awareness campaign focused on the relationship between social media usage, mental well-being, and personal relationships, particularly among students. They have collected a unique dataset and require your expertise to uncover key insights. The goal is to provide evidence-based recommendations for educational programs, digital literacy initiatives, and potential policy suggestions to promote healthier social media engagement.

## The task
Your task is to analyze this dataset to identify patterns, correlations, and potential risk factors associated with social media use, its impact on student relationships, and overall well-being. Your findings will be instrumental in shaping the DWI's next set of public health advisories and intervention strategies.

- Document all your steps and thoughts, so the mentors can follow your process
- Prepare a nice README.md for your project
- Think about how you can present your results for different target groups

## Some guidance (optional, if needed)
Your analysis can address the following questions, categorized by complexity.
If you want to add or do others, feel free to do so. 
If you can find additional data that suits your original dataset, feel free to implement it.

### Beginner Questions
- Data Loading and Initial Exploration:
    - Load the dataset into a pandas DataFrame.
    - Display the first 5 rows, check data types, and identify the number of unique values in categorical columns (e.g., Gender, Academic_Level, Most_Used_Platform, Country, Relationship_Status, Conflicts_over_Social_Media).
    - Identify and handle any missing values.
    - Provide descriptive statistics for numerical columns
- Usage Patterns:
    - What is the average Average_Daily_Usage_Hours across all students?
    - Which Most_Used_Platform is the most popular among the surveyed students? Visualize the distribution.
    - How does Average_Daily_Usage_Hours vary by Gender and Academic_Level?
- Basic Impact Assessment:
    - What is the distribution of Impact_on_Academic_Performance categories?
    - Calculate the average Sleep_Hours for students reporting "Positive", "Negative", and "Neutral" impacts on academic performance.
- Addiction Score Basics:
    - What is the average Addiction_Score in the dataset?
    - How does the Addiction_Score relate to Average_Daily_Usage_Hours? (e.g., calculate correlation or visualize with a scatter plot).
- Relationship Conflicts Overview:
    - What percentage of students report Conflicts_over_Social_Media?
    - Is there a noticeable difference in Average_Daily_Usage_Hours or Addiction_Score between students who report conflicts and those who don't?
### Intermediate Questions
- In-depth Addiction and Well-being Analysis:
    - Explore the correlation between Addiction_Score, Mental_Health_Score, and Sleep_Hours. Are there strong positive or negative relationships? Visualize these relationships (e.g., using a correlation heatmap or scatter plots).
    - How does Addiction_Score vary across different Most_Used_Platforms? Which platforms are associated with higher average addiction scores?
- Social Media Impact on Relationships:
    - Analyze the relationship between Conflicts_over_Social_Media and Addiction_Score/Average_Daily_Usage_Hours. Do higher usage/addiction scores correspond to more reported conflicts? Quantify this relationship.
    - Investigate if Relationship_Status influences Average_Daily_Usage_Hours or Addiction_Score, or vice versa.
- Segmenting Student Behaviors:
    - Can you identify different clusters or segments of students based on their social media usage habits (Average_Daily_Usage_Hours, Addiction_Score), sleep patterns, and mental health scores? (e.g., using K-Means clustering, if appropriate).
    - Describe the characteristics of each identified segment.
- Geographical and Demographic Insights:
    - Are there significant differences in Addiction_Score or Average_Daily_Usage_Hours across different Countrys?
    - How do Age and Academic_Level influence social media usage and its reported impacts?
### Policy and Program Recommendations (Qualitative):
- Based on your findings, what are 2-3 critical insights you would share with the Digital Wellness Institute regarding the impact of social media on students?
- Propose concrete recommendations for educational programs or digital literacy initiatives aimed at fostering healthier social media habits among students, supported by your data analysis.

Remember to provide clear visualizations and concise explanations for all your findings. Your analysis will help the DWI develop impactful strategies for digital well-being!
