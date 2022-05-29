# Movie_Recommendation_System
Building a movie recommendation system using User-Based Collaborative Filtering(UBCF) approach that will recommend movies based on user's historic data.

## Dataset
IMDB(Movies and Rating)
Movies - 10329 rows and 3 columns
Rating - 105339 rows and 4 columns

## What is UBCF method?
User-based Collaborative Filtering is a type of Memory-based Collaborative Filtering that uses all user data in the database to create recommendations.

## Cosine Similarity
Cosine similarity is a measure of finding similar users. It is used to compute the similarity between two users. To compute the similarity we use the given formula:

![render](https://user-images.githubusercontent.com/87423118/170865999-d67e855d-94ef-46cc-a89a-5aed7472e0bb.png)

if the resultant value is 1 then users are said to be identical and if the value is 0 then they are said to be dissimilar.

## Steps Involved
1. Data Pre-processing
2. Normalization
3. Creating recommender model
4. Recommending movies to user


