# Welcome to the Repository of Group2 in Sommer2025

# Social Media Addiction vs Relationships

## Digital Wellness Institute (DWI) Student Analysis Project

###Overview

Welcome to the project for the **Digital Wellness Institute** (DWI). This analysis investigates the impact of **social media usage** on **students' mental well-being**, **academic performance**, **personal relationships**, and **addiction behaviors** using data from a Kaggle dataset:
[Social Media Addiction vs Relationships](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships/data)

---

###Project Objective

The DWI is launching a new awareness campaign and seeks data-driven insights to:

* Understand patterns in social media usage among students.
* Assess its impact on mental health, academic performance, and personal relationships.
* Develop actionable strategies and recommendations for promoting **healthy digital habits**.

---

###Dataset Summary

* **Source**: Kaggle
* **Format**: CSV
* **Records**: Student responses from a digital well-being survey.
* **Key Features**:

  * `Gender`, `Age`, `Country`, `Academic_Level`, `Most_Used_Platform`
  * `Average_Daily_Usage_Hours`, `Addiction_Score`, `Mental_Health_Score`, `Sleep_Hours`
  * `Relationship_Status`, `Conflicts_over_Social_Media`, `Impact_on_Academic_Performance`

---

###Tasks Completed

#### 1. Data Exploration

* Loaded the dataset using Pandas.
* Displayed sample rows, data types, and unique categorical values.
* Checked and handled missing values.
* Descriptive statistics for numerical features.

#### 2. Beginner-Level Analysis

* Most used social media platforms distribution.
* Average usage hours by gender and academic level.
* Impact on academic performance vs. sleep hours.
* Addiction score correlation with daily usage.

#### 3. Intermediate-Level Analysis

* Correlation heatmap of mental health, sleep, and addiction scores.
* Platform-wise addiction score comparison.
* Relationship conflicts vs. addiction and usage metrics.
* Analyzed differences based on relationship status.
* Clustering of student behavior using K-Means.

#### 4. Demographics & Geographic Insights

* Country-wise comparison of social media addiction and usage.
* Influence of age and academic level on social media patterns.

#### 5. Key Insights & Recommendations

Based on data patterns, we propose:

* Digital literacy education for early academic levels.
* Sleep hygiene and screen-time awareness campaigns.
* Support programs for students reporting high addiction scores and conflicts.

---

###Key Visualizations

* Bar Chart               – Most used social media platforms
* Box Plots               – Usage patterns by gender and academic level
* Heatmap                 – Correlation matrix among key numeric variables
* Scatter Plots           – Addiction vs. usage and sleep hours
* Pie Charts              – Conflict distribution, platform breakdown
* K-Means Cluster Plot    – Behavior-based segmentation

---

###Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (for clustering)
* Google Collab (see `DS.ipynb`)

---

### File Structure

```
📁 Social-Media-Addiction-Analysis
│
├── DS.ipynb              # google collab with all analyses
├── README.md             # Project summary and documentation
├── data/
│   └── Social_Media_Data.csv   # Raw dataset (from Kaggle)
```

---

##Stakeholder	Application

Students                        	- Awareness of their digital behavior and risks
Educators                       	- Curriculum updates and digital literacy training
Mental Health Professionals      	- Early warning signs and behavior profiling
Policymakers                    	- Data to support national or institutional guidelines
Parents & Guardians             	- Understanding youth digital engagement

---

###Top Insights

1. **Addiction scores** are strongly correlated with **lower sleep hours** and **poorer mental health**.
2. Students with **conflicts in relationships** due to social media also tend to have higher daily usage and addiction scores.
3. Platforms like **Instagram** and **TikTok** are linked to higher usage and addiction rates compared to LinkedIn or Twitter.

---

###Recommendations

* **Digital Literacy**: Integrate social media education in academic curricula.
* **Wellness Programs**: Promote balance with screen-time reduction challenges.
* **Support Systems**: Offer counseling to students affected in relationships.
* **Policy Advocacy**: Encourage campus-wide digital detox days or social media usage caps during exam seasons.

---

###License

This project is for educational and awareness purposes under the **Digital Wellness Institute Initiative**.
