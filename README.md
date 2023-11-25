# CryptoClustering

Requirements
Find the Best Value for k by Using the Original Data (15 points)
To receive all points, you must:

Code the elbow method algorithm to find the best value for k. Use a range from 1 to 11. (5 points)

To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k. (5 points)

Answer the following question: What’s the best value for k? (5 points)

Cluster the Cryptocurrencies with K-Means by Using the Original Data (10 points)
To receive all points, you must:

Initialize the K-means model with four clusters by using the best value for k. (1 point)

Fit the K-means model by using the original data. (1 point)

Predict the clusters for grouping the cryptocurrencies by using the original data. Review the resulting array of cluster values. (3 points)

Create a copy of the original data, and then add a new column of the predicted clusters. (1 point)

Using hvPlot, create a scatter plot by setting x="price_change_percentage_24h" and y="price_change_percentage_7d". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents. (4 points)

Optimize the Clusters with Principal Component Analysis (10 points)
To receive all points, you must:

Create a PCA model instance, and set n_components=3. (1 point)

Use the PCA model to reduce the features to three principal components. Then review the first five rows of the DataFrame. (2 points)

Get the explained variance to determine how much information can be attributed to each principal component. (2 points)

Answer the following question: What’s the total explained variance of the three principal components? (3 points)

Create a new DataFrame with the PCA data. Be sure to set the coin_id index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame. (2 points)

Find the Best Value for k by Using the PCA Data (10 points)
To receive all points, you must:

Code the elbow method algorithm, and use the PCA data to find the best value for k. Use a range from 1 to 11. (2 points)

To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k. (5 points)

Answer the following questions: What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data? (3 points)

Cluster the Cryptocurrencies with K-means by Using the PCA Data (10 points)
To receive all points, you must:

Initialize the K-means model with four clusters by using the best value for k. (1 point)

Fit the K-means model by using the PCA data. (1 point)

Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values. (3 points)

Create a copy of the DataFrame with the PCA data, and then add a new column to store the predicted clusters. (1 point)

Using hvPlot, create a scatter plot by setting x="PC1" and y="PC2". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents. (4 points)

Visualize and Compare the Results (15 points)
To receive all points, you must:

Create a composite plot by using hvPlot and the plus sign (+) operator to compare the elbow curve that you created from the original data with the one that you created from the PCA data. (5 points)

Create a composite plot by using hvPlot and the plus (+) operator to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data. (5 points)

Answer the following question: Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means? (5 points)

Coding Conventions and Formatting (10 points)
To receive all points, you must:

Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. (3 points)

Name functions and variables with lowercase characters, with words separated by underscores. (2 points)

Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (3 points)

Use concise logic and creative engineering where possible. (2 points)

Deployment and Submission (10 points)
To receive all points, you must:

Submit a link to a GitHub repository that’s cloned to your local machine and that contains your files. (4 points)

Use the command line to add your files to the repository. (3 points)

Include appropriate commit messages in your files. (3 points)

Code Comments (10 points)
To receive all points, your code must:

Be well commented with concise, relevant notes that other developers can understand. (10 points)
