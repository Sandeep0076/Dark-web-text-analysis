# Dark-web-text-analysis
In this work, a dataset of articles collected from Darkweb is given. My task is to analyze the data and get the intuition what's going on. What the people are talking without going through each an every article.

To perform the analysis, following Work is done :

* Cleaned the text.
* Applied all the preprocessing steps like:
    * Removing stopwords
    * lowercase
    * tokenization (tf-idf)
    * lemmetization
    * vectorization
    
* As the dataset was huge, used Principle Component Analysis (PCA) for dimensionality reduction.

* Thereafter clustered the documents so that I can segregate the similar kind of documents for that I Used K-means clustering for clustering.

*  Thereafter for visulization of the clustered data in 2D I used t-SNE.

* Further On each cluster documents, I did topic modeling as each document can contain multiple topics : for that I used LDA (Latent Dirichlet Allocation)
* Then extracted keywords for each clusters. To create a visual wordcloud
* In another work on same dataset. Did an analysis of 5 different text extractive summarization
* In the last Extracted summary is created for each cluster.
