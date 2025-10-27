\# Milestone 2 – Clustering and Pattern Detection

\### Study Track AI-Based Student Study Habit Recommender



\## Objective

To analyze student academic performance patterns by clustering students based on their math, reading, and writing scores. The goal is to identify distinct performance groups that can inform personalized study recommendations.



\## Dataset Source

\- \*\*Source:\*\* Student Performance Dataset (1000 student records)

\- \*\*Features used for clustering:\*\* `math score`, `reading score`, `writing score`

\- \*\*Additional features:\*\* `gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`



\## Steps Followed

1\. \*\*Data Loading:\*\* Loaded the student performance dataset into Google Colab.

2\. \*\*Feature Selection:\*\* Selected numerical features (`math score`, `reading score`, `writing score`) relevant for academic performance clustering.

3\. \*\*Data Standardization:\*\* Applied `StandardScaler` to normalize all score features to ensure equal contribution to clustering.

4\. \*\*Dimensionality Reduction:\*\* Used Principal Component Analysis (PCA) with 2 components for effective visualization of clusters.

5\. \*\*Optimal Cluster Determination:\*\* Applied the Elbow Method to determine the optimal number of clusters (k=3).

6\. \*\*Clustering Implementation:\*\* Performed K-Means clustering and assigned cluster labels to each student.

7\. \*\*Cluster Analysis:\*\* Added cluster labels as a new column and calculated summary statistics for each cluster.

8\. \*\*Visualization Creation:\*\* Generated multiple visualizations including scatter plots, bar charts, correlation heatmaps, and cluster distribution charts.



\## Tools Used

\- \*\*Platform:\*\* Google Colaboratory

\- \*\*Data Processing:\*\* pandas, numpy

\- \*\*Machine Learning:\*\* scikit-learn (StandardScaler, PCA, KMeans)

\- \*\*Visualization:\*\* matplotlib, seaborn

\- \*\*Statistical Analysis:\*\* Elbow Method for optimal cluster selection



\## Key Insights and Graphs



\### Visualizations Created:

\- \*\*`cluster\_scatter.png`:\*\* 2D scatter plot showing student clusters in PCA space with distinct color coding

\- \*\*`cluster\_profile\_bar.png`:\*\* Bar chart comparing average math, reading, and writing scores across clusters

\- \*\*`correlation\_heatmap.png`:\*\* Correlation matrix showing relationships between academic performance features



\### Cluster Analysis Results:

\- \*\*Cluster -1 (Low Performers):\*\* Students with much lower scores, likely needing significant intervention.

&nbsp; - Average Math Score: 25.56

&nbsp; - Average Reading Score: 30.67

&nbsp; - Average Writing Score: 26.78



\- \*\*Cluster 0 (Moderate/High Performers):\*\* Students with good scores, showing balanced academic performance.

&nbsp; - Average Math Score: 66.46

&nbsp; - Average Reading Score: 69.52  

&nbsp; - Average Writing Score: 68.43



\### Key Patterns Identified:

\- Strong positive correlation between math, reading, and writing scores

\- Clear separation of students into distinct performance tiers

\- Potential for targeted interventions based on cluster membership

\- Foundation for personalized study habit recommendations



\## Conclusion

The clustering analysis successfully identified two distinct student performance groups based on academic scores. This segmentation provides a solid foundation for the AI-based study habit recommender system, enabling tailored strategies for different performance levels. Moderate/high performers can receive advanced challenges and balanced support, while low performers would benefit from intensive intervention programs.



\## Next Steps for Study Habit Recommender

\- Analyze demographic factors within each cluster

\- Develop personalized study recommendations for each cluster

\- Implement recommendation algorithms based on cluster characteristics

\- Validate recommendations through student feedback and performance tracking



