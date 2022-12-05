# Unsupervised machine learning using clustering and cryptocoins. 

This project used Unsupervised machine learning algorithms to cluster coins together. hvPlot and Plotly were used to visulaize some of the data to show supply and coins mined.
Pre-processing the data involved changing the data types, removing columns and making sure they were no nulls or variables that would interfere with machine learning algorithms. Columns were dropped where needed and get_dummies was used to make sure variables were integers. 

PCA was done to reduce dimensions as the number of variables grew with the pre processing of data. 
Elbow curve showed how many clusters might be optimal for this excercise with the bend being at 4. Plotly express was then used to plot clusters predicted by k-means model.

Total coin supply vs. Total Coins Mined showd some more data about the crypto coins and hover capability was able to be used to see which coins fell where on the chart. 
