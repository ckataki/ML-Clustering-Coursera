# README #

This is the IPython repository for the Machine Learning: Clustering course of Coursera. We will use KD-trees, Gaussian models using expectation-minimization (EM), Latent Dirichlet Allocation (LDA), and Map-Reduce techniques on clustering problems.

### Week 1: Use nearest-neighbors search, and Locality Sensitive Hashing (LSH) to cluster Wikipedia pages. ###
    * Gain intuition for different notions of similarity and practice finding similar documents.
    * Explore the tradeoffs with representing documents using raw word counts and TF-IDFs.
    * Explore the behavior of different distance metrics by looking at the Wikipedia pages most similar to President Obama’s page.
    * Implement the LSH algorithm for approximate nearest neighbor search.
        - Examine the accuracy for different documents by comparing against brute force search, and also contrast runtimes.
        - Explore the role of the algorithm’s tuning parameters in the accuracy of the method
### Week 2: Use k-means clustering to cluster Wikipedia pages. ###
    * Explore the role of random initialization on the quality of the clustering.
    * Explore how results differ after changing the number of clusters.
    * Evaluate clustering, both quantitatively and qualitatively.
### Week 3: Use an EM implementation to fit a Gaussian mixture model with diagonal covariances to a subset of the Wikipedia dataset. ###
    * Fitting a diagonal covariance Gaussian mixture model to text data, and compare with k-means clustering.
    * Give a meaningful interpretation to the fitted parameters in the EM model.
    * Implement the EM algorithm for a Gaussian mixture model.
        - Apply the implementation to cluster images.
        - Explore clustering results and interpret the output of the EM algorithm.
### Week 4: Fit a Latent Dirichlet allocation (LDA) model on Wikipedia text data. ###
    * Apply standard preprocessing techniques on Wikipedia text data.
    * Use GraphLab Create to fit a Latent Dirichlet allocation (LDA) model.
    * Explore and interpret the results to analyze the impact of a mixed membership approach, including topic keywords and topic assignments for documents.
    * Identify the topics discovered by the model in terms of their most important words, and predict the topic membership distribution for a given document.
### Week 5: Explore hierarchical clustering. ###
    * Build a hierarchy of clusters using a top-down approach.
    * Recursively bipartitioning the Wikipedia data using k-means clustering.

### How do I get set up? ###

* Python version: 2.7.12
* GraphLab Create: greater than 1.8.5
* Dependencies: Numpy, Matplotlib, Scipy, scikit-learn, IPython