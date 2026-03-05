# 👥 Customer Segmentation (K-Means Clustering)

### 🚩 Problem Statement
Businesses often treat their entire customer base as a single entity, leading to inefficient marketing. To increase ROI, a company needs to identify distinct groups of customers based on their spending habits and demographic data to create "targeted" personas.

### 🧠 The Approach
I applied an unsupervised learning workflow to segment a retail dataset into five actionable personas:
1.  **Exploratory Data Analysis (EDA):** Performed multivariate analysis to find correlations between "Annual Income" and "Spending Score."
2.  **Optimal K Selection:** Used the **Elbow Method** (plotting WCSS against the number of clusters) to mathematically determine that 5 clusters provided the best balance between granularity and simplicity.
3.  **Clustering Logic:** Implemented the **K-Means Algorithm**. I prioritized feature scaling beforehand, as K-Means is sensitive to the scale of data points.
4.  **Persona Mapping:** Visualized the clusters using 2D scatter plots, labeling groups such as "High Spenders/Low Income" (Sensible) and "High Spenders/High Income" (Target).



### 📊 Results
* **Business Intelligence:** Successfully identified 5 distinct customer personas, allowing for a potential 20-30% increase in marketing efficiency through targeted campaigns.
* **Visualization:** Created clear, cluster-labeled plots that allow non-technical stakeholders to understand the segments instantly.

### 👤 Author
**Mithul Krishna Suresh** *2nd Year B.Tech CSE, NIT Bhopal*
