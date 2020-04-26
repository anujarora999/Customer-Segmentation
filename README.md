# Customer-Segmentation Of Retail Shop Using K - Means 

A VISUAL INTRODUCTION TO K-MEANS ALGORITHM

In machine learning, computers apply Unsupervised learning techniques to automatically find similarities in the data point and group similar data points together.

Using Online Retail dataset about Sales, a machine learning model K-Means Clustering is performed to segment the customers into respective groups based on their RFM scores.

First, some intuition
Let’s say you had to determine which are your best Customers from your sales data. In machine learning terms, grouping similar data points is a Clustering task.
Determining the RFM scores

Recency    (R) : Days since last purchase
Frequency (F) : How many times a customer has purchased 
Monetary  (M) : How much do they spend

Based on the above factors RFM score of the sales data is determined. A final RFM score is calculated simply by combining individual RFM scores.

Grouping similar entities together help profile the attributes of different groups. In other words, this will give us insight into underlying patterns of different groups.

There are many applications of grouping unlabeled data, for example, you can identify different groups/segments of customers and market each group in a different way to maximize the revenue.


Date	Recency	Frequency	Monetary	Rank	R_Quartile	F_Quartile	M_Quartile	RFM_Score

Customer Id			

- 2010-12-12	362	7	34000	37.5	2	2	1	221
- 2010-12-14	360	7	46000	27.5	4	2	2	422
- 2010-12-06	368	2	12000	50.0	1	1	1	111
- 2010-12-14	360	9	57000	13.5	4	3	3	433
- 2010-12-13	361	8	50000	21.0	3	2	3	323


### Pre-Processing & Visualization

•	Pre-processing of the data is performed in which the missing data is identified and evaluated.
•	Data is normalized for transforming values of several variables into a similar range.
•	Correlation of the factors are determined and Visualized using Heat map.

 

### Applying K-Means Algorithm
- Finding patterns in data is where machine learning comes in. One example of a unsupervised machine learning method is a K-Means algorithm.

- It starts with K as the input which is how many clusters you want to find. Place K centroids in random locations in your space.

- Now, using the Euclidean distance between data points and centroids, assign each data point to the cluster which is close to it. 

- Recalculate the cluster centers as a mean of data points assigned to it.

- Repeat the above steps until no further changes occur.


### The Output
No. of Clusters (n) = 2
 
Fig : Plot between Frequency & Recency

•	The yellow cluster has a centroid represents the "low value customers"

•	The dark blue cluster has a centroid represents the "high value customers"


As a result the clusters are formed which indicates the no. of low & high value customers.
