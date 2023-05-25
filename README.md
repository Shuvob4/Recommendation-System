# Recommendation-System

In our project, we tried to implement a recommendation system using amazon beauty products data, we choose a smaller subset of amazon dataset. 
Dataset was downloaded from https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/, it's publically available for academic purposes. 
The datasets are in json format and there are two dataset, review_data and meta_data. Due to large file size i could not upload the file.


I have implemented 5 algorithms to build our Recommendation System based on Amazon Product Review (Beauty Product) Dataset. 
List of Algorithms: 
1. Demographic Model with weighted function 
2. Item Based Collaborative Filtering (KNNWithMeans) 
3. Model Based Collaborative Filtering (SVD) 
4. User Based Collaborative Filtering (SVD++) 
5. User Based Collaborative Filtering (SVD) 
And used evaluation metric like recall, precision and RMSE. 

I have used surprise from scikit-learn. Need to install it if not installed before.
If you are using Anaconda Run Below Command

conda install -c conda-forge scikit-surprise

