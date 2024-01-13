# Forecasting-with-AR-and-ARIMA-Models
The project "Forecasting with AR and ARIMA Models" employs advanced statistical techniques to analyze and predict crime rates across different states. The initial phase involves data preprocessing and normalization, where the crime data is uploaded into Python, and a `rates_df` data frame is created. Normalization is crucial for clustering as it ensures that all features are on a similar scale, enabling more effective analysis. The Z-score method is applied to achieve this, and the importance of normalized data in clustering is explained. 

Subsequently, hierarchical clustering is utilized to classify states based on normalized crime data. The average linkage method is employed, and a dendrogram is presented with a cluster threshold of 3.3. Cluster membership and analysis of cluster characteristics based on normalized mean values are provided, offering valuable insights into the distinct groups formed. Additionally, cluster labeling based on common features or variable means is presented, enhancing the interpretability of the results.

Following hierarchical clustering, the project delves into k-means clustering with k = 6. The Elbow chart is used to determine the appropriate number of clusters, and a data frame with normalized cluster centroids is created. Profile plots of normalized centroids are analyzed to gain insights into cluster characteristics. The comparison between hierarchical and k-means clustering concludes that while both methods offer valuable insights, k-means clustering provides a clearer separation of the dataset, making it more suitable for identifying distinct groups within states' crime rates. This project contributes to a deeper understanding of crime patterns and facilitates informed decision-making in law enforcement and policy planning.
