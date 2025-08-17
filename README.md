In this project, I implemented a Movie Recommendation System using the MovieLens 100K dataset. The dataset contains 100,000 ratings from 943 users on 1,682 movies. The system was developed and tested in Google Colab.

The recommendation pipeline includes three different approaches:

User-Based Collaborative Filtering (CF):

Computes similarities between users based on their movie ratings.

Recommends movies that similar users have rated highly.

Item-Based Collaborative Filtering (CF):

Computes similarities between movies based on user ratings.

Recommends movies that are most similar to the ones a user has already liked.

Matrix Factorization using Singular Value Decomposition (SVD):

Decomposes the user-item rating matrix into latent factors.

Predicts unseen ratings and generates top-N personalized recommendations.

To evaluate the system, Precision@5 was calculated, which measures the fraction of recommended movies in the top-5 that the user actually rated highly (≥ 4). For the sample test user, Precision@5 was low because the recommended movies did not overlap with their highest ratings. However, the system demonstrates the implementation of different recommendation strategies successfully.
