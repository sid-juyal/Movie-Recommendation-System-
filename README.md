# Movie-Recommendation-System

### Methodology:
Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

How Cosine Similarity works? 

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
![143417796-8602832b-aac9-4f4f-b930-b753dc050981](https://user-images.githubusercontent.com/65865527/207930812-9c960988-c76a-462c-8a9b-446495daf7b3.png)

### Description
An end-to-end Movie Recommendation System Application.
The dataset that I have used here is the TMDB 5000 Movie Dataset. Under this dataset, there are 2 files:
1. tmdb_5000_movies.csv: It includes 20 columns like budget, genres, id, keywords, title, tagline, etc.
2. tmdb_5000_credtis.csv: It includes 4 columns- movie_id, title, cast, and crew.
My Recommender model takes a movie title as input and predicts top-n most similar movies based on the tag. 
Also, I have this project as a web app hosted on localhost with the help of streamlit.

### Input:
![input](https://user-images.githubusercontent.com/65865527/207927747-c7ac2996-3ebe-446a-bcf4-1cddcd87d959.png)

### Output:
![output](https://user-images.githubusercontent.com/65865527/207927839-5d272ea3-36dc-4063-b408-35c05cb1f1a3.png)

### User Interafce:
![ui1](https://user-images.githubusercontent.com/65865527/207927971-20f88cd9-9425-4b88-907f-e2b26002b23f.png)

![ui2](https://user-images.githubusercontent.com/65865527/207928006-720dbffe-98d2-4609-b774-fd3166bcb436.png)
