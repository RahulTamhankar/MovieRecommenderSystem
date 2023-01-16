# MovieRecommenderSystem

Recommender systems: What are they?
A significant group of machine learning algorithms known as recommender systems provide users with "appropriate" recommendations. All three sites—YouTube, Amazon, and Netflix—use recommendation systems that suggest the next movie or item to you based on your browsing history (content-based filtering) or the browsing histories and preferences of other users who share your interests (Collaborative Filtering).

![1_QbBtk_xjwQWDW7aCrmGwfw-e1625635853618](https://user-images.githubusercontent.com/87760177/212707600-2bdec3ca-254c-4c11-9871-3db241aae501.jpeg)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Project Flow-
I have used a Kaggle dataset OF TMDB which is a movie rating website- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

After reading the data from dataset I have performed data preprocessing. Dropping unwanted columns since I am making a content based recommender system, I am only keeping those features which will help me create a TAG to make recommendations. I have also done Stemming using nltk library. I have done text vectorization(by also removing stop words) using Bag of words technique. This bag of words will be used to create matrix factorization. I have every movie in a vector form on a 5000D Space. It is a Sparse matrix Python ie.If most of the elements of the matrix have 0 value, then it is called a sparse matrix. The recommendation is also performed with the help of Cosine Similarity.
![image](https://user-images.githubusercontent.com/87760177/212707336-8041bfc5-19bc-4ce1-aed5-c7c0304fb6f7.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

After this in order to carry out the front end and displaying this recommender system I have used StreamLit which is an open source app framework in Python language. It helps us create web apps for data science and machine learning in a short time. This is implemented in PyCharm.
Here is the result of my recommender system using StremLit-

![image](https://user-images.githubusercontent.com/87760177/212705831-28106e9e-50c2-456d-ae61-a5f88c22fe4c.png)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Deployment-
The final step is the deployment. I have deployed the app with the help of Heroku Deployment and here is the link- https://movierecommendersystemrahul.herokuapp.com/

![image](https://user-images.githubusercontent.com/87760177/212706646-b28b816f-d561-4e9b-8848-e1ef46b5b666.png)

