# Recommendation-Systems
This project involved building recommendation systems for e-commerce products. A popularity-based model and a collaborative Filtering model were used and evaluated to recommend top-10 products for a user.
Problem Statement - 
Build your own recommendation system for products on an e-commerce website like Amazon.com.
Online E-commerce websites like Amazon, Filpkart uses different recommendation models to provide different suggestions to different users. 
Amazon currently uses item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real time. This type of filtering matches each of the user's purchased and rated items to similar items, then combines those similar items into a recommendation list for the user.
In this project we are going to build recommendation model for the electronics products of Amazon. 
The dataset here is taken from the below website. 
Source - Amazon Reviews data (http://jmcauley.ucsd.edu/data/amazon/)  The repository has several datasets. For this case study, we are using the Electronics dataset.

Dataset columns - first three columns are userId, productId, and ratings and the fourth column is timestamp. You can discard the timestamp column as in this case you may not need to use it.

Project details:
I have to used collaborative filtering model instead content based filtering works on basis of product/ item attributes. 
Collaborative filtering also uses user behavior in addition to product attributes. 
This method has 2 approaches one is user based & another one is item based approach.

Conclusion:

The dataset very highly sparse model.
After taking subset of the data it looks like less items are available so getting very high RMSE value
After taking the subset of data, datset has become unfit for mostly item based recommendation system
Also the dataset rating count plot shows that there are many items have given ratings as 5 which are is giving biased result so high RMSE
