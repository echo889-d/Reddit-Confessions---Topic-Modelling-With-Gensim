# Reddit-Confessions---Topic-Modelling-With-Gensim
Get it off your chest! 

In this project, I will compare these 3 techniques: Kmeans clustering, Latent Semantic Analysis and Latent Dirichlet Allocation (LDA), to get the hidden topics of each data point, and explore clustering methods to analyze what topics most people confess about on Reddit.

This is an unsupervised learning project, so we do not have true cluster labels. In each model, I will tune parameters to find the optimal number of topics and interpret each topic. The evaluation methods are topic coherence values for LDA and LSA, and silhouette coefficient scores for Kmeans clustering.

I also discuss about the challenges and solutions when dealing with a million data, such as mini-batches and online learning are helpful to speed up the process while not taking too much memory. LDA method works the best to extract hidden topics among the three topics, based on the coherence values. It extracts 18 topics, covering  work, family, school, friends, relationships, and many other aspects. What can be done to make improvement is that there are other parameters can be tuned, different evaluation methods can be used, and more topic modelling models that can be used, to test and improve the goodness of fit for the data.

Steps include:
1. Data Preprocessing
2. Implement models: K-means clustering, Latent Semantic Analysis and Latent Dirichlet Allocation
3. Results and Evaluation
