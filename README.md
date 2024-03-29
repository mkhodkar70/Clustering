# Clustering
Unsupervised Learning -- Hierarchical Clustering, K-Means and K-Modes Algorithms, PCA, etc.

1) Footwear Product Segmentation (Product_Segmentation): <br>
Hierarchical and k-means clustering techniques have been leveraged to cluster several thousands of Nike and Adidas products 
into a handful of segments, based on attributes such as listing price, sale price, discount and rating. Distinctive features
of different clusters have then been compared against each other using cluster profiling. <br>
Key tools: K-Means Clustering, Agglomerative Clustering, Segmentation, Cluster Profiling <br>
Libraries: scikit-learn, scipy.cluster, yellowbrick, matplotlib, seaporn, numpy, pandas

2) RNA Sequencing Analysis of Cancer Tumors (Gene_Analysis): <br>
The gene expression data provided by RNA sequencing has been transformed into a much lower-dimensional space utilizing Principal
Component Analysis so that at least 80% of the variance is retained. The results of PCA have then been contrasted against those of 
the visualization/clustering technique known as t-distributed Stochastic Neighbor Embedding. <br>
Key tools: Dimensionality Recuction, Reduced-Order Modeling, Principal Component Analysis, t-SNE Clustering <br>
Libraries: scikit-learn, numpy.linalg, matplotlib, seaporn, numpy, pandas


3) Stock Segmentation for an Investment Management Firm (Stock_Clustering): <br>
In order to devise personalized investment strategies for clients, an asset management firm has provided the stock data of a
wide variety of companies present on NYSE, and has requested an ML-based solution for grouping of the stocks into distinct and 
interpretable clusters, using their attributes such as current price, price change, volatility index, cash ratio, cash flow and
P/E ratio. <br>
Key tools: K-Means Clustering, Hierarchical Clustering, Cluster Profiling <br>
Libraries: scikit-learn, scipy.cluster, yellowbrick, matplotlib, seaporn, numpy, pandas


4)  Segmentation of NPR Articles (Topic_Modeling): <br>
About 12,000 articles from NPR, written in 2016 and '17, have been clustered into appropriate topics, using matrix 
decomposition and probabilistic techniques, specifically tailored for the task of text segmentation. At the end,
the results, performances and computational costs of both methods have been compared. <br>
Key tools: Non-Negative Matrix Factorization, Latent Dirichlect Allocation, TF-IDF and Count Vectorization <br>
Libraries: scikit-learn (text feature extraction), sklearn.decomposition, spacy, Ipython.display, numpy, pandas


5) Personalization via Segmentation (CruiseSegmentation): <br>
Segmentation of the customers of a cruise line, using a dataset of 20,000 guests, containing features such as their age, income,
socioeconomic background, no. of previous cruises, embarkment month and duration of the trip, for the purpose of personalized 
communication, which in turn boosts response and conversion rates. <br>
Key tools: Exploratory Data Analysis, K-Modes Clustering, Cluster Profiling <br>
Libraries: kmodes.kprototypes, scikit-learn, scipy, yellowbrick, matplotlib, seaporn, numpy, pandas
