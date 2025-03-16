# Section B

## Question: 
Given a pool of data of mobile device information that these users are using ie. Brand,model, design a model to determine the eligibility of individuals for obtaining a loan using device data. Take into account that not all device attributes are readily available all the time and there is no historical data available.


## Solution

We can categorize all smartphones into groups using unsupervised learning algorithms like K-Means Clustering and analyze the device attributes within each cluster. This helps us understand how device attributes vary across different groups. In the future, we can identify anomalies by detecting devices with attributes that do not align with any of the observed clusters.

Notebook Link: 

## Data Source,Python library used and model choosen
Collected Smart phones Sales data from this link : [link](https://www.kaggle.com/datasets/yaminh/smartphone-sale-dataset/data)
Python library used: Pandas, Numpy, Scikit-Learn
Model used: K-Means Clustering



