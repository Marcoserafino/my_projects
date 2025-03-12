
# Customer segmentation with clustering (K-Means)

This project focuses on analyzing customer data to identify distinct groups or segments based on shared characteristics, such as monetary value, frequency, and recency of purchases. By applying the K-Means clustering algorithm, the project groups customers into clusters where members of the same cluster are more similar to each other than to those in other clusters. 


## Authors

- [@Marcoserafino](https://github.com/Marcoserafino)

## Steps & Analysis

*Data Preprocessing*:
The customer data is first loaded and cleaned by checking for missing values.  Features like monetary value, frequency, and recency were obtained through feature engineering. These features were then scaled using StandardScaler to ensure consistency in their range, which is crucial for the performance of clustering algorithms like K-Means.

### *Modeling*:
The K-Means clustering algorithm is applied to the preprocessed customer data. The optimal number of clusters (K) is determined using methods like the elbow method or silhouette score. The K-Means model groups the customers into distinct segments based on their purchasing behavior.

### *Model Evaluation*:
Since clustering is an unsupervised learning technique, the evaluation focuses on measuring the quality of the clusters. We use metrics such as silhouette score to assess how well-separated and cohesive the clusters are. Visualizations like scatter plots and cluster centroids help in interpreting and validating the resulting segments.



### *Result*: 
The K-Means clustering algorithm successfully identified 4 well-separated customer segments. Each cluster represents a distinct group of customers with unique behaviors based on monetary value, frequency, and recency. These insights allow us to tailor marketing strategies and actions for each group, such as targeted promotions for high-value customers or retention efforts for those with lower engagement.


### Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- KMeans (from scikit-learn)
- StandardScaler (from scikit-learn)



