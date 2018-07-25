# KNN
K Nearest Neighbors Model in Python

Example of when we can use KNN
Suppose we have Horses vs Dogs and our data are weights and Heights. 
If we compare these two dimension in a scatterplot, we'll see clearly that we could classify
the animals in 2 different areas.

Steps of the model:
1. Calculate the distance from x to all points in your data
2. Sort the point in your data by increasing distance from x
3. Predict the majority label of the "k" closest point

Choosing a "k", will affect what class a new point is assiged to
k indicates the number of point to consider around x considering circles,
the higher k the bigger the circle that will include more points

Model PROs and CONs -->
PROs: very simple,training is trivial,works with any number of classes, 
    easy to add more data, few parameters (k,Distance Metric)
CONs: High Prediction Cost (worse for large data sets), 
    not good with high dimensional data, categorical features don't work well
    
This model is supervised. This mean that we know our target variable, so what we want to 
predict. When we create a machine learning model it is important to evaluate it to see its 
performance. For this reason we need to split the data in 2 parts. The first part 
(usually 70-80%) is used to train the model and the second one to test it.
