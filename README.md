# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING

   ![netflix-image](https://images.unsplash.com/photo-1574375927938-d5a98e8ffe85?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8bmV0ZmxpeHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=800&q=60)

## 📖 Introduction

This project aims to cluster the video content available on Netflix based on the company’s site
data. Apart from aiding in the development of an efficient recommendation system, clustering
the video content would also provide information about the type of content the company is
interested in listing on its site. Thus giving an insight to content creators and filmmakers on
the type of video content in demand.


## 📖 EDA Observations

The notable observations identified during EDA were:
1. Most movies streaming on the platform were released after 2010. A large portion of the
TV Shows streaming on the platform was released after 2015. The year 2017 had the
highest number of movie and TV show releases on the platform. Netflix began adding
videos to the platform in 2008 and started aggressively adding video content in 2017.
2. It was also found that more stand-alone movies were added as compared to TV shows.
The majority of the content is rated for Mature Audiences and for audiences over 14
years old.
3. Drama is the most produced genre in the top non-English speaking countries with
exception of Japan and South Korea. Japan is the biggest producer of Anime across the
platform which is also the leading genre in Japan. Romance is the most produced
genre in South Korea. 
4. It is noted that Comedy was the most produced genre in
English-speaking countries like the United States of America, the United Kingdom and
Canada. Documentaries are predominantly produced in the United Kingdom and the
United States of America
5. Duplicates of TV shows were made corresponding to their seasons. Upon doing so, it was
observed that the TV shows signed have been higher than the movies in 2016
6. Although, the movies signed have been higher than TV shows ever since it was prominent
that the TV shows signed per year were catching up to the movies signed annually. Hence, we
can conclude that it was true that Netflix had been showing more interest in TV shows as
compared to movies

## 📖 Feature Engineering 

* Upon Text Preprocessing, unigram and bigram word clouds of different genre descriptions on
Netflix were created to get insight on content plots. 
* These textual attributes were vectorised using TFIDF to be processed effectively.
* It was decided that the textual attributes are to be used to model video content into topics
using Latent Dirichlet Allocation. 
* This would make sure that all the topical information about video content was captured without putting any available information to waste. 
* Apart from this, it also entertained the possibility of a video exhibiting multiple themes at different
extents by expressing the probability a document belongs to a given topic. 
* The highest coherence score was achieved by modelling nine topics.


## 📖 Results

* The performance of three unsupervised machine learning algorithms, namely DBSCAN,
K-means and Hierarchical Clustering was evaluated and compared to cluster Netflix movies
and TV shows.

* DBSCAN clustered the content into 9 clusters with a silhouette score of 0.4664, Davies-Bouldin
Index of 1.62 and Calinski-Harabasz Score of 2510.76.

* For K-Means clustering the elbow and optimal silhouette score were found at 8 clusters with a
silhouette score of 0.4686, Davies-Bouldin Index of 0.887 and Calinski-Harabasz Score of
2901.84.

* For Hierarchical clustering, the dendrogram distance was optimal at a distance of 20 with
eight clusters producing a silhouette score of 0.46867 Davies-Bouldin Index of 0.889 and
Calinski-Harabasz score of 2900.28.

## 📖 Conclusions

* In conclusion, a comprehensive exploratory data analysis was performed, and the content
trends produced across different countries were studied. 
* It was found that it was true that Netflix had been showing more focus on TV shows as compared to movies.
* Apart from this, the video content on Netflix’s catalogue was clustered into eight clusters with
a silhouette score of 0.47 with K-mean and Hierarchical Clustering Algorithms. 
* This labelled content can be further studied and explored to determine what type of content is on-demand,
potentially providing an intuition to content creators about the type of content Netflix is interested in listing on its catalogue.

## 📖 References
1. DBSCAN Clustering Algorithm in Machine Learning | KDNuggets
2. Evaluate Topic Models: Latent Dirichlet Allocation (LDA) | by Shashank
Kapadia | Towards Data Science.
3. Agglomerative Clustering and Dendrograms — Explained | by Satyam Kumar
| Towards Data Science.
4. Understanding Topic Coherence Measures | by João Pedro | Towards Data
Science
5. Hierarchical Clustering: Agglomerative and Divisive — Explained |by Satyam
Kumar| Towards Data Science|

## 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run locally on Jupyter Notebook or on Google Colab via browser.

## 📜 Credits
* Project done by Mahin Arvind Chanthira Sekaran
* Verified by Almabetter

## ☎ Contact

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/mahinarvind/) [![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/mahin-arvind) [![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@mahinarvindds) [![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)](https://drive.google.com/file/d/1Hg5poNigBXo8cxisb9KjLc-H7Qy-Epsg/view?usp=share_link)

