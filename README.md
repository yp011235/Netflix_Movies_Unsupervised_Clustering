# Netflix Movies Unsupervised Clustering

Summary: After thoroughly exploring and then cleaning, I trained 3 different unsupervised clustering models on a text-based dataset; Netlfix movies with descriptions and relevant people involved. With this expereince using NLP, I am able to clean text-based data through techniques and tools like stopwords  and the frequency of keywords being used throughout the dataset.

Attribute Information:
1. show_id
2. type
3. title
4. director
5. cast
6. country
7. date_added
8. release_year
9. rating
10. duration
11. listed_in
12. description

Tools:
TransactionEncoder: to onehot encode our text
NLTK: to use their stopwords
PCA: for dimensionality reduction

Unsupervised Clustering Models:
KMeans
DBScan
Agglomerative

Evaluation Metrics:
Silhouette Score: It displays a measure of how close each point in a cluster is to points in the neighbouring clusters.
