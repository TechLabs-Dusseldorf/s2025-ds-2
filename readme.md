# Social Media Usage & Addiction Analysis

## 1. Project Overview
This project studies how students use social media and how it affects their sleep, mental health, academic performance, and relationships.  

The data comes from surveys where students shared:  
- How many hours they use social media per day  
- Their sleep time and mental health score  
- If social media caused conflicts in their relationships  
- Their academic level, country, and most-used platform  

The goal is to find patterns and risks in social media usage and give recommendations for healthier digital habits.

---

## 2. Installation and Requirements  

### Requirements  
You need the following installed:  
- Python (version 3.8 or later)  
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn  

### How to Install  
Open a terminal (or Anaconda Prompt) and run:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```  

This will install everything needed to run the project.  

---

## 3. How to Run the Project
There are two ways to run:

### Option 1: Jupyter Notebook / Google Colab
- Open `Structured_code.ipynb` in Jupyter or Google Colab.  
- Run the cells step by step to see data cleaning, analysis, and graphs.  

### Option 2: Python Script
- Run the script from terminal:
  ```bash
  python structured_code.py
  ```
- This will load the dataset, clean it, create graphs, and save processed files like:
  - `students_social_media_cleaned.csv`  
  - `students_social_media_with_clusters.csv`  

---

## 4. Analysis Summary

### Main Findings
- Average daily usage: Students spend several hours on social media each day(Average 4.9).  
- Addiction score: Higher usage hours are strongly linked to higher addiction scores.  
- Academic performance: Students with heavy use often report negative impact on studies and lower sleep hours.  
- Conflicts: A large percentage of students say social media causes conflicts in relationships.  
- Mental health: High addiction scores connect with lower mental health scores and less sleep.  
- Platform differences: Some platforms show higher average addiction scores than others.  
- Clusters (student groups):
  - Low-use group: Balanced usage, better sleep, healthier scores  
  - Moderate-use group: Medium usage, some conflicts, mixed mental health  
  - High-use group: Very high usage, poor sleep, high addiction, more conflicts  

### Graphs
The notebook shows:  
- Bar charts of most used platforms  
- Boxplots (e.g., daily usage by gender/academic level)  
- Correlation heatmaps (addiction vs sleep vs mental health)  
- Scatter plots (usage vs addiction)  
- Clustering plots (groups of students)  

---

## 5. Results and Recommendations

### Results
- Strong link between daily hours and addiction level.  
- Negative effect of heavy social media on sleep and mental health.  
- Relationship conflicts rise with higher addiction scores.  
- Different patterns depending on age, country, and platform.  

### Recommendations
1. Education programs Teach students about balancing screen time and sleep.  
2. Digital literacy Encourage awareness about how platforms affect mental health.  
3. Healthy habits Suggest regular breaks, setting daily limits, and prioritizing offline activities. 
