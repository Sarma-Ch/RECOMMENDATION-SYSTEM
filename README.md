# RECOMMENDATION-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: CHAVALI NARASIMHA SARMA

INTERN ID: CT06DM1358

DOMAIN: MACHINE LEARNING

DURATION: 6 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

DESCRIPTION:

A Recommendation System is a specialized software application designed to suggest items to users based on their previous behaviors, preferences, and interactions. These systems aim to assist users in discovering

relevant and interesting items they may not have found on their own. From online shopping to streaming platforms, recommendation systems are widely used today to enhance user satisfaction and drive business

growth.

There are three types of Recommendation system:

Content Based filtering: This method recommends items similar to those a user has liked in the past. It works by analyzing the features of items such as genre, category, or keywords. For example, if a user enjoys action movies, the

system will recommend other action-packed films.

Collaborative Filtering: This technique makes recommendations by identifying users with similar preferences and suggesting items they have liked. It does not rely on the content of the items but rather on user interaction data like

ratings. It can be either user-based or item-based.

Hybrid Systems: These systems combine content-based and collaborative filtering methods to provide more accurate and reliable recommendations. This approach is commonly used in real-world applications like Netflix, Amazon,

and Spotify to enhance user personalization.

Importance of Recommendation System:

1.Improves user experience

2.Increases Engagement

3.Drives revenue to the company.

The recommendation system uses Collaborative Filtering, Matrix Factorization and Cosine similarity. The collaborative filtering is based on user to user similarity. The Matrix factorization reduces the

dimensionality using SVD and the cosine similarity is to find similar users.

Project Approach:

1.pandas is used for data manipulation and data analysis.

2.numpy is used for numerical computing

3.sklearn is a powerfull machine learning python library used for data preprocessing, model training and evaluation..

sklearn.decomposition is used for dimensionality reduction and feature extraction it contains PCA,TruncatedSVD,Factor Analysis..

sklearn.metrics.pairwise is used to evaluate pairwise diatance or affinity of sets of samples, this module contains both distance metrics and kernels.

Frist Step is to create a user-item matrix in this ratings.piviot_table is used to tranforms the dataframe into a matrix and .fillna(0) is used to fill all the missing values.

Second Step is to apply TruncatedSVD for Matrix Factorization.

Third Step is to compute cosine similarity it measures the angle between two user matrices.

Fourth Step is to convert the Similarity matrix to a Dataframe.

Next is a function to get top n similar users.

Next is a function to recommend movies to the similar users.

The final step is taking user input and displaying recommendations.

This recommendation system uses a user-based collaborative filtering approach, enhanced through SVD for dimensionality reduction and cosine similarity for identifying similar users. The system is efficient and

interpretable, providing movie suggestions based on historical user preferences while also evaluating its performance using RMSE. Though basic, this pipeline illustrates the core principles behind more advanced

recommender systems and can be extended using features like implicit feedback, hybrid models, or deep learning.

Dataset: The dataset used for the this program is ml-latest-small the dataset conatins 5 CSV files

1.links.csv conatins links of movies
2.movies.csv contains the names of movies
3.ratings.csv contains all the ratings for all the moves
4.tags.csv contains tags of the movie
Totally the dataset contains 100,836 entries from ratings.csv and 9,742 entries from movies.csv.

OUTPUT:

1.ratings.csv:

![Image](https://github.com/user-attachments/assets/7069d592-4c0c-46cf-b34f-bfdd3fdeab53)

2. movies.csv:
![Image](https://github.com/user-attachments/assets/1befbad9-e098-4d44-8317-db34a844674b)

3.Evaluation results and recommendation system output:
![Image](https://github.com/user-attachments/assets/cf1e16d9-70b4-464e-ae2f-c69f860c8d0f)



