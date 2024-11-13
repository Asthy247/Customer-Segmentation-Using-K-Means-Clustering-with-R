# Customer-Segmentation-Using-K-Means-Clustering-with-R
# Introduction

**Problem Statement:** 
The goal of this project is to segment customers based on their demographic and behavioral characteristics using K-Means clustering. 

By understanding customer segments, businesses can tailor their marketing strategies, product offerings, and customer experiences to 

better meet the needs and preferences of different customer groups.   

# Dataset:

The dataset used for this analysis is the "Mall_Customers" dataset available on Kaggle. 

It contains the following features:

**•	CustomerID**: A unique identifier for each customer.

**•	Gender:** The gender of the customer.

**•	Age: **The age of the customer.

**•	Annual Income: **The annual income of the customer in thousands of dollars.  

**•	Spending Score**: A score assigned to each customer based on their spending behavior, ranging from 1 to 100.  

# Data Analysis and Visualization

# Exploratory Data Analysis for Mall Customers

**Summary Statistics for Age Distribution**

![image](https://github.com/user-attachments/assets/9a10a837-3e43-41c0-86b0-78589b1c7238)

**Age Distribution of Customers:**

**•	Minimum Age:** The youngest customer is 18 years old.

**•	First Quartile (Q1):** 25% of the customers are 28 years old or younger.

**•	Median Age:** The median age of the customers is 36 years old.

**•	Mean Age:** The average age of the customers is 38.85 years old.

**•	Third Quartile (Q3):** 75% of the customers are 49 years old or younger.

**•	Maximum Age: **The oldest customer is 70 years old.

# Standard Deviation for Age

The Standard Deviation (SD)for Age was carried out and the result is at 13.96901

This means that, on average, the ages of customers in the dataset deviate from the mean age (38.85 years) by approximately 13.97 years.

W**hat does this tell us?**

**•	Spread of Ages**: A higher standard deviation indicates a wider spread of ages in the dataset. In this case, the relatively high standard deviation suggests that the ages of customers are quite diverse.

•	**Potential for Segmentation:** The variation in ages can be leveraged to identify different customer segments based on age and tailor marketing strategies accordingly.

•	**Outliers: **A high standard deviation might also indicate the presence of outliers, which could be investigated further to understand their impact on the overall analysis.

# Summary Statistics for Annual Income
![image](https://github.com/user-attachments/assets/1b3ef266-585e-4de3-95c7-9dcfcd7fef52)

Based on the summary statistics provided, we can observe the following about the annual income distribution of customers:

**•	Minimum Income:**The lowest annual income in the dataset is $15,000.


**•	First Quartile (Q1):** 25% of the customers have an annual income of $41,500 or less.


**•	Median Income:** The median annual income is $61,500.


**•	Mean Income:** The average annual income is $60,560.


**•	Third Quartile (Q3):** 75% of the customers have an annual income of $78,000 or less.


**•	Maximum Income:** The highest annual income is $137,000.


**Interpretations and Potential Insights:**

**•	Income Range:** The dataset covers a wide range of annual incomes, from low-income to high-income individuals.


**•	Income Distribution:** The distribution of income is likely skewed to the right, with a few high-income individuals.


# Summary Statistics for Age

![image](https://github.com/user-attachments/assets/55a0a181-2627-4cc5-82cc-db468528825d)

**•	Minimum Age:** The youngest customer is 18 years old.

**•	First Quartile (Q1): **25% of the customers are 28 years old or younger.

**•	Median Age:** The median age of the customers is 36 years old.

**•	Mean Age:** The average age of the customers is 38.85 years old.

**•	Third Quartile (Q3):** 75% of the customers are 49 years old or younger.

**•	Maximum Age:** The oldest customer is 70 years old.

**Intrepretation of the Results:**

**•	Diverse Age Range:** The data suggests a diverse range of customer ages, catering to different demographics.

**•	Middle-Aged Dominance: **The median age of 36 indicates that a significant portion of the customers are middle-aged.

**•	Potential Target Groups:** The distribution can be used to identify target age groups for specific marketing campaigns or product offerings.

**•	Outliers:** The minimum and maximum ages might be outliers, which could be investigated further to understand their impact on the overall analysis.

**The Standard Deviation (SD) of Spending Score: 25.82352**

This value indicates the degree of variation or dispersion in the spending scores of customers. 

A higher standard deviation suggests that the spending scores are more spread out from the mean.

**Interpretation:**

**•	Variability in Spending Habits:** The high standard deviation implies that there is a significant difference in spending habits among customers. Some customers spend much more than others.

# Data Visualization and Insight

# Bar Chart for Gender Comparison

![image](https://github.com/user-attachments/assets/70621f4d-bfc2-40d1-ac20-da051118f45e)

we can observe the following about the gender distribution:

**•	Female Dominance:** The bar for "Female" is significantly taller than the bar for "Male," indicating that there are more female customers in the dataset.

**•	Gender Imbalance:** The dataset appears to be skewed towards female customers.


# Pie Chart for Gender Distribution

![image](https://github.com/user-attachments/assets/b591c412-954d-4fea-b2b5-8c7ef8b79b3e)

We can observe the following about the gender distribution:

**•	Female Dominance:** Approximately 56% of the customers are female.

**•	Male Minority:** Approximately 44% of the customers are male.

# Histogram for Age Distribuition

![image](https://github.com/user-attachments/assets/58d97f81-eda4-4b55-bf2a-e7d399308dfb)

**Key Observations from the Histogram:**

**Peak Age Group:** The histogram shows a peak around the 30-35 age group, indicating a significant number of customers in this age range.
   
**Age Range:** The age range of the customers is approximately 20 to 70 years.

**Distribution Shape:** The distribution appears to be roughly unimodal, with a single peak.

**Potential Outliers:** There might be a few outliers at the higher end of the age range.

# Box Plot for Age Distribution

![image](https://github.com/user-attachments/assets/8e4fd567-de54-4d11-a2e2-66c514dddc89)

**Key Observations from the Boxplot:**

**Median Age:** The median age appears to be around 35 years. This is represented by the thick line within the box.

**Interquartile Range (IQR):** The box represents the IQR, which is the range between the 25th and 75th percentiles. In this case, the IQR seems to be around 15-20 years.

**Whiskers**: The whiskers extend to the minimum and maximum values, excluding outliers.

**Outliers:** There appear to be a few outliers on the higher end of the age range, as indicated by the individual points beyond the whiskers.

# Histogram for Annual Income

![image](https://github.com/user-attachments/assets/81157ef6-9046-49d8-9693-43e003d2c5ed)

**Key Observations:**

**•	Right-Skewed Distribution**:The histogram shows a right-skewed distribution, indicating that most customers have lower annual incomes,

while a smaller proportion have significantly higher incomes.


•	**Peak Around 60:** The peak of the distribution is around the 60k annual income range, suggesting that this is the most common income bracket for customers.


**•Outliers**: There are a few customers with very high annual incomes, as indicated by the bars on the right side of the histogram.

# Density Plot for Annual Income

![image](https://github.com/user-attachments/assets/6225d1ac-2772-4c7e-8be8-2ff711e745a7)

**Key Observations:**

•	**Right-Skewed Distribution:** The density plot confirms the right-skewed distribution of annual income, 
indicating that a majority of customers have lower to moderate incomes, while a smaller portion has significantly higher incomes.


**•	Peak Around 60:** The peak of the density curve is around the 60k annual income range, suggesting that this is the most common income bracket for customers.

**•	Tailing Off:** The curve gradually tails off towards higher income levels, indicating fewer customers in the higher income brackets.


**Interpretations and Potential Insights:**

**•	Target Market Segmentation:** The distribution suggests that the customer base is diverse, with both low-income and high-income individuals. 

Businesses can identify target segments based on income levels and tailor marketing strategies accordingly.

**•	Product and Pricing Strategies:** The income distribution can inform product and pricing strategies to cater to different income segments.


# Descriptive Statitsits for Spending Score**

![image](https://github.com/user-attachments/assets/0d482732-6b80-4b1c-9b99-151a7ce6e846)

**•	Summary Statistics:**

**•	Minimum:** 1.00

**•	1st Quartile (Q1):** 34.75

**•	Median:** 50.00

**•	Mean:** 50.20

**•	3rd Quartile (Q3)**: 73.00

**•	Maximum:** 99.00


**•	Interpretation:**

**•	Range:** The spending scores range from 1 to 99, indicating a wide range of spending behaviors among customers.

**•	Central Tendency:** The median (50.00) is slightly lower than the mean (50.20), suggesting a slightly right-skewed distribution.

**•	Spread:** The interquartile range (IQR, Q3-Q1) is 38.25, indicating a significant spread in spending scores.

**•	Potential Outliers**: The minimum value of 1 might be considered an outlier, as it is significantly lower than the rest of the data.

# Box Plot Visualization for Spending Score

![image](https://github.com/user-attachments/assets/88996e4d-5024-4d87-b629-feb5e463ea4d)

**Key Observations from the Boxplot:**

**Median**:The median spending score is around 50. This indicates that half of the customers have a spending score below 50 and half have a score above 50.

**Interquartile Range (IQR)**: The IQR, represented by the box, seems to be relatively small. 

This suggests that a significant portion of the customers have spending scores clustered around the median.

**Whiskers**: The whiskers extend to the minimum and maximum values, excluding outliers.

In this case, the whiskers are relatively short, indicating that there are no extreme outliers in the data.

**Outliers:** There don't appear to be any significant outliers in the data, as there are no data points beyond the whiskers.

# Histogram Visualzation for Spending Score

![image](https://github.com/user-attachments/assets/7491e249-97b6-4bac-b5a0-908b7492bb8c)

**Key Observations:**

**•	Bimodal Distribution:** The histogram shows two distinct peaks, suggesting two potential customer segments based on spending behavior.

**•	High-Spending Segment**: A significant number of customers have high spending scores, possibly representing affluent or luxury shoppers.

**•	Low-to-Medium Spending Segment**: Another group of customers exhibits lower to moderate spending behavior.


# K-Nearest Neighbors (KNN) Algorithm
K-Nearest Neighbors (KNN) is a simple yet powerful supervised machine learning algorithm used for both classification and regression tasks. 

It classifies new data points based on the majority vote of its k nearest neighbors.   

**How KNN Works:**

Choose the value of K: Determine the number of nearest neighbors to consider.

Calculate Distance: Calculate the distance between the new data point and all training data points. Common distance metrics include Euclidean distance and Manhattan distance.
	
Select Nearest Neighbors: Identify the k nearest neighbors based on the calculated distances.

Classification: For classification, assign the new data point to the class that is most frequent among its k nearest neighbors.

Regression: For regression, calculate the average value of the target variable for the k nearest neighbors and assign that value to the new data point.

**Key Points:**

**•	Simplicity:** KNN is relatively easy to understand and implement.

**•	Versatility:** It can be used for both classification and regression tasks.

**•	Flexibility:** The choice of the distance metric and the value of k can influence the performance of the algorithm.

**•	Computational Cost:** KNN can be computationally expensive for large datasets, as it requires calculating distances to all training points.

**Clustering**

Clustering is an unsupervised machine learning technique used to group similar data points together. It aims to discover hidden patterns and structures within the data.  

**K-Means Clustering:**

K-Means is a popular clustering algorithm that partitions data into k clusters based on similarity. It works as follows:

**Initialize Cluster Centers:** Randomly select k data points as initial cluster centers.

**Assign Data Points:** Assign each data point to the nearest cluster center based on a distance metric (e.g., Euclidean distance).

**Update Cluster Centers:** Calculate the mean of all data points assigned to each cluster and update the cluster centers.

**Iterate:** Repeat steps 2 and 3 until the cluster assignments no longer change.


**Key Points:**

**•	Simplicity:** K-Means is relatively easy to understand and implement.

**•	Efficiency:** It is computationally efficient, especially for large datasets.

**•	Sensitivity to Initial Conditions**: The initial choice of cluster centers can affect the final clustering results.

**•	Assumptions:** K-Means assumes that clusters are spherical and of equal size.

By understanding the principles of KNN and K-Means clustering, you can effectively apply these techniques to various data analysis tasks.


# Elbow Plot Visualization

![image](https://github.com/user-attachments/assets/bc450b23-0b51-4829-9789-451d16c246e7)

The elbow plot is a useful tool for determining the optimal number of clusters in a k-means clustering analysis. It shows the relationship between the number of clusters (K) and the total within-cluster sum of squares (WSS).

In this plot, we can observe:

**•	Steep Decline:** As the number of clusters increases from 1 to 4, there's a significant decrease in the WSS. This indicates that adding more clusters significantly improves the model's ability to explain the data.

•	**Elbow Point:** Around K=4, the rate of decrease in WSS starts to slow down. This "elbow point" suggests that adding more clusters beyond 4 might not significantly improve the model's performance.

**Optimal Number of Clusters:**
Based on the elbow plot, the optimal number of clusters appears to be 4. Beyond this point, the decrease in WSS becomes less pronounced, indicating diminishing returns.

# Silhouette Plot Visualization
# Silhouette Plot Visualization for K=2 Clusters

![image](https://github.com/user-attachments/assets/f0b73451-2131-4f58-acd5-076d948c9343)

**Understanding the Silhouette Plot**
A silhouette plot is a visualization tool used to assess the quality of a clustering solution. It provides insights into how well each data point fits within its assigned cluster compared to other clusters.

**•**Silhouette Width****: Each vertical bar represents a data point. The height of the bar indicates the silhouette width of that data point.

**•	Cluster Assignments:** The data points are grouped into clusters, and each cluster is represented by a set of bars.

**•	Silhouette Coefficient:** The average silhouette width for the entire clustering solution is displayed at the bottom of the plot.

**Interpretation of the Given Plot:**

**•Cluster Separation**:** The two clusters appear to be well-separated, as indicated by the distinct groupings of bars.

**•Cluster Cohesion:** The bars within each cluster are relatively tall, suggesting that the data points within each cluster are closely related.

•	**Average Silhouette Width:** The average silhouette width of 0.29 indicates a moderately good clustering solution. A higher value would indicate better-defined

# Silhouette Plot Visualization for K=3 Clusters

![image](https://github.com/user-attachments/assets/2dd41c24-b906-4b4f-b4e5-2be378a59d0e)

**Key Observations from the Plot:**

**•	Cluster Separation**: The three clusters appear to be relatively well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion**: Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.38 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.


**Interpreting the Silhouette Widths:**

**•	Silhouette Width for Cluster 1:** The average silhouette width of 0.50 indicates that, on average, data points in this cluster are fairly well-separated from other clusters.

**•	Silhouette Width for Cluster 2:** The average silhouette width of 0.28 suggests that, on average, data points in this cluster are less well-separated from other clusters.

**•	Silhouette Width for Cluster 3:** The average silhouette width of 0.60 indicates that, on average, data points in this cluster are well-separated from other clusters.


# Silhouette Plot Visualization for K=4 Clusters

![image](https://github.com/user-attachments/assets/a0ee72da-e90d-4e5f-9b7f-9e1414d547ca)

**Key Observations from the Plot:**

**•	Cluster Separation:** The four clusters appear to be relatively well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion:** Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.41 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.

# Silhouette Plot Visualization for K=5 Clusters

![image](https://github.com/user-attachments/assets/a7a21bf9-4cd7-426a-a6f4-48ff15bae6d5)

**Key Observations from the Plot:**

**•	Cluster Separation:** The five clusters appear to be relatively well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion:** Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.44 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.

# Silhouette Plot Visualization for K=6 Clusters

![image](https://github.com/user-attachments/assets/5d4d9cb2-7e01-4050-8bd6-26c4c494ff34)

**Key Observations from the Plot:**

**•	Cluster Separation:** The six clusters appear to be reasonably well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion**: Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.45 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.


# Silhouette Plot Visualization for K=7 Clusters

![image](https://github.com/user-attachments/assets/aa12c560-b5a8-4a01-8632-d0dc4904bab7)


**Key Observations from the Plot:**

**•	Cluster Separation:** The seven clusters appear to be relatively well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion:** Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.44 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.

# Silhouette Plot Visualization for K=8 Clusters

![image](https://github.com/user-attachments/assets/5ba10d6d-6762-4f36-ba62-acdb7f120f16)

**Key Observations from the Plot:**

**•	Cluster Separation:** The eight clusters appear to be relatively well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion:** Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.43 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.


# Silhouette Plot Visualization for K=9 Clusters

<img width="224" alt="image" src="https://github.com/user-attachments/assets/20beddf6-978e-4fbd-971b-cc479a70e30f">

**Key Observations from the Plot:**

**•	Cluster Separation:** The nine clusters appear to be reasonably well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion**: Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width**: The average silhouette width of 0.39 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.


# Silhouette Plot Visualization for K=10 Clusters
![image](https://github.com/user-attachments/assets/ffbbf59e-7a9e-4485-96b9-5aaf91263c47)

**Key Observations from the Plot:**

**•	Cluster Separation:** The ten clusters appear to be relatively well-separated, as indicated by the distinct groupings of bars.

**•	Cluster Cohesion:** Within each cluster, the bars are generally tall, suggesting that the data points are closely related to each other.

**•	Average Silhouette Width:** The average silhouette width of 0.38 indicates a moderately good clustering solution. A higher value would indicate better-defined clusters.

# Elbow Plot for Optimal Number of Clusters

![image](https://github.com/user-attachments/assets/3a8fdb8f-a7fc-4c4e-899b-94bf396087f9)

**Understanding the Plot:**

The elbow plot is a visualization technique used to determine the optimal number of clusters in a k-means clustering analysis. It plots the average silhouette width against the number of clusters.

**Interpreting the Plot:**

**•	Increasing Silhouette Width:** As the number of clusters increases, the average silhouette width generally increases.

This is because with more clusters, data points can be assigned to more specific groups, leading to better separation.


**•	The Elbow Point:** The "elbow point" is the point where the rate of increase in the average silhouette width starts to diminish. 
In this plot, the elbow point appears to be around k=6.


# Gap Statistic Method

The Gap Statistic Method is a statistical method used to determine the optimal number of clusters in a dataset. 

It compares the total within-cluster dispersion of your data to the dispersion of randomly generated data sets.

**How it works:**

**Calculate the Within-Cluster Dispersion:**

For a given number of clusters (k), calculate the total within-cluster dispersion (W(k)) of your actual data.

This measures how tightly clustered the data points are within each cluster.

**Generate Random Data:**
	
Create a set of reference datasets by randomly sampling from the range of your actual data.

**Calculate Within-Cluster Dispersion for Random Data:**
	
For each random dataset, calculate the total within-cluster dispersion (Wk*) for different numbers of clusters (k).

**Calculate the Gap Statistic:**

o	The gap statistic for a given number of clusters (k) is calculated as: 

o	Gap(k) = E[log(Wk*)] - log(W(k))

**Determine the Optimal Number of Clusters:**

The optimal number of clusters is the value of k where the gap statistic starts to level off. This is often referred to as the "elbow point."


**Interpretation:**

•	A larger gap statistic indicates a better clustering solution.

•	The optimal number of clusters is the one that maximizes the gap statistic.

**Advantages of the Gap Statistic Method:**

**•	Objective Criterion:** It provides an objective way to determine the optimal number of clusters.

**•	Avoids Subjectivity**: Unlike methods like the elbow method, which can be subjective, the gap statistic provides a more quantitative approach.

**In Conclusion:**
The gap statistic method is a valuable tool for determining the optimal number of clusters in a dataset. 
By comparing the clustering structure of the actual data to random data, it provides a more objective and reliable way to evaluate different clustering solutions.

# Result for Clustering

![image](https://github.com/user-attachments/assets/62409c21-7109-41a3-bf92-22f38d303761)

**Understanding the Output:**

The provided output shows the results of a clustering analysis, likely using the K-Means algorithm. Let's break down the key components:


**1.	Data:**

o	The first few rows of the data are displayed, showing the features used for clustering: Age, Annual.Income..k.., and Spending.Score..1.100..

**2.	Clustering Vector:**

o	This vector assigns each data point to a specific cluster. For example, the first data point belongs to cluster 1, the second to cluster 4, and so on.

**3.	Within-Cluster Sum of Squares**:

o	This shows the sum of squared distances between data points and their respective cluster centroids for each cluster. Lower values indicate tighter clusters.

**4.	Between-Cluster Sum of Squares:**

o	This measures the variation between clusters. A higher between-cluster sum of squares indicates better separation between clusters.

**5.	Total Sum of Squares:**

o	This is the total variation in the data.

**6.	Between-SS / Total-SS:**

o	This ratio indicates the proportion of variance explained by the clustering. A higher value indicates a better clustering solution.

**Interpreting the Results:**

Based on the output, we can infer that the clustering algorithm has identified distinct groups of customers based on their age, annual income, and spending score.

The clusters with lower within-cluster sum of squares are likely more tightly packed, indicating that the data points within those clusters are more similar to each other.

# Visualization for K-Means Clustering Results (Annual Income)

![image](https://github.com/user-attachments/assets/2942915e-9603-4440-bdb5-676cba757451)

The scatter plot visualizes the clustering results obtained using the K-Means algorithm on the Mall_Customers dataset. 

Each dot represents a customer, and the color of the dot indicates the cluster to which the customer belongs.

**Key Observations:**

**•	Distinct Clusters**:The plot clearly shows six distinct clusters of customers, each with a unique pattern of spending scores and annual income.

**•	Cluster 1:** This cluster represents customers with high spending scores and high annual income. They are likely affluent customers who are willing to spend on luxury items.

**•	Cluster 2:** This cluster represents customers with moderate spending scores and high annual income. They may be more budget-conscious or prefer value-for-money products.

**•	Cluster 3**: This cluster represents customers with low spending scores and low annual income. They are likely price-sensitive and may prioritize basic necessities.

**•	Cluster 4:** This cluster represents customers with moderate spending scores and moderate annual income. They may be a generalist group with diverse spending habits.

**•	Cluster 5**: This cluster represents customers with high spending scores and moderate annual income. They may be willing to spend on premium products and services.

**•	Cluster 6**: This cluster represents customers with low spending scores and moderate annual income. 

They may be more budget-conscious or have specific needs that drive their spending behavior.


# Visualization for K-Means Clustering Results (Spending Score)

![image](https://github.com/user-attachments/assets/61c7fcf4-ac0d-414d-8932-ab7d848c6831)

**Key Observations:**

**•	Distinct Clusters:** The plot clearly shows six distinct clusters of customers, each with a unique pattern of spending scores and age.

**•	Cluster 1:** This cluster represents older customers with moderate to high spending scores. They may be retirees or individuals with disposable income.

**•	Cluster 2:** This cluster represents younger customers with high spending scores. They may be young professionals or students with disposable income.

**•	Cluster 3:** This cluster represents middle-aged customers with moderate spending scores. They may be families or individuals with stable incomes.

**•	Cluster 4:** This cluster represents younger customers with low spending scores. They may be students or young professionals with limited budgets.

**•	Cluster 5:** This cluster represents older customers with low spending scores. They may be retired individuals with fixed incomes or individuals with specific needs.

**•	Cluster 6:** This cluster represents middle-aged customers with high spending scores. They may be affluent individuals or professionals with high disposable incomes.


# Visualization for K-Means Clustering Results (Classes)

![image](https://github.com/user-attachments/assets/feef9392-4b9d-4e3f-b90b-1a97829bd3a3)

**Key Observations:**

**•	Distinct Clusters:** The plot shows several distinct clusters of data points, indicating that the K-Means algorithm has successfully identified underlying patterns in the data.

**•	Cluster Separation:** The clusters appear to be well-separated from each other, suggesting that the algorithm has effectively grouped similar data points together.

**•	Cluster Density**: Some clusters appear to be denser than others, indicating that these clusters contain more data points.

# Conclusions:

The customer dataset exhibits a wide range of ages, incomes, and spending behaviors.

K-Means clustering can be a valuable tool to segment customers based on these characteristics.

By understanding different customer segments, the team can develop targeted marketing

strategies and product offerings to better meet customer needs and preferences, potentially increasing sales and customer satisfaction.
