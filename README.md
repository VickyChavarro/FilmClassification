
- The project focused on grouping users based on their movie ratings using unsupervised learning techniques, with the aim of improving the segmentation and personalisation of recommendation systems on streaming platforms and other digital services.
  
- The motivation behind the project lies in the importance of providing personalised recommendations, especially in a digital environment where the vast amount of available content can be overwhelming for users.
  
- To address this problem, several clustering approaches were implemented, including K-means, Agglomerative Clustering and a combination of Agglomerative Clustering with Non-Negative Matrix Factorisation (NMF). These methods were selected for their ability to identify patterns in the data without the need for labels or supervision.
  
- Dimensionality reduction techniques such as PCA (Principal Component Analysis) and NMF were applied to facilitate data visualisation and capture latent representations of user preferences.

- In relation to the clustering algorithms employed, K-means was utilised to establish the initial clusters. However, it exhibited deficiencies with regard to the compactness and homogeneity of the clusters formed, particularly in instances of high internal dispersion within certain clusters. Agglomerative Clustering, a hierarchical approach, was found to significantly improve cluster structure and size, creating more balanced groups with lower dispersion. Nevertheless, the integration of NMF with Agglomerative Clustering emerged as the optimal strategy, yielding more compact and homogeneous clusters, despite the unevenness in cluster sizes.
  
- The findings demonstrated that the combination of Agglomerative Clustering with NMF yielded clusters characterised by minimal intra-cluster distances and effective separation between clusters, signifying an effective grouping of users with similar preferences. The subsequent characterisation of the clusters yielded the identification of diverse cinematic preferences, ranging from a predilection for iconic 90s movies to a proclivity for contemporary science fiction and action-oriented productions.
