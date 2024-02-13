# Book-Recommendation-System-with-Machine-Learning

Developed a book recommendation using collaborative filtering using K-Nearest Neighbors

For Testing purposes took a books database from a public domain containing book values, users and ratings

# Objective

Acheiving collaborative filtering with K - Nearest Neighbors algorithm to arrive at a recommendation list of nearest books

# Prerequisites

Install following packages:

pip install numpy 
pip install pandas 
pip install sklearn
pip install keras 
pip install seaborn
pip install scipy

# Model Building

kNN is a machine learning algorithm to find clusters of similar users based on common book ratings, and make predictions using the average rating of top-k nearest neighbors.

Now we will group by book titles and create a new column for total rating count.

We then transform the values(ratings) of the matrix dataframe into a scipy sparse matrix for more efficient calculations.

# Conclusion

The knn algorithm simply calculates the distance of a particular entity across all the entries and computes the nearest neighbors and gives the distances accordingly.

If we specify neighbors values as 6 we will get a recommendation list of 6 entries that are closer to the given entry.

# Deployment

We are using streamlit for deploying our trained model. We are exporting the model through pickle format
