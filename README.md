# Crypto Clustering 
By Kiana Navarre

**Programming Language Used: Python, SKLearn**\
**Concepts Explored: Unsupervised Machine Learning**

## Description
The purpose of this project is to use a test data set examining crypto currency data to examine the effects of using fewer features to cluster data.  This is done by examining k-means clustering both prior to and post optimization by Principal Component Analysis (PCA). 

## Procedure
The following steps were performed to perfom the analysis: 
1. Prepare the Data by using the StandardScaler() module from scikit-learn.
2. Find the k Value using the Original Scaled DataFrame
3. Cluster Cryptocurrencies with K-means using the Original Scaled Data
4. Optimize Clusters with Principal Component Analysis
5. Find the Best Value for k using the PCA Data 
6. Cluster Cryptocurrencies with K-means Using the PCA Data 

## Analysis Questions
1. What is the best value for k using the original data? 
   - Answer: The best value for k is 4. 
2. What is the total explained varienace of the three principal components used in the PCA model? 
   - Answer: The total explained variance is 0.895 (or 89.5%)
3. What is the best value for k when using the PCA data? 
   - Answer: 4
4. Does the k value found using the PCA data differ from that found using the original data. 
   - Answer: No, it does not differ.  Both k values are 4. 
5. After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-means? 
   - Answer: Using fewer features results in clusters that appear more clearly separated. This can be seen by comparing the scatter plots for both. The clusters created using the PCA data are more easily discernable, with the outliers being clearly separated. 
