# Cryptocurrencies
Unsupervised machine learning

## Project Overview
Utilizing the machine learning technology to group cripto coins into clusters of common features

## Module challenge

### Objective
Perform data cleaning and processing using dataframes and non supervised machine learning algorithm

### Results 
•	Crypto currency data was cleaned and prepared for ML processing. I used sklearn package with KMeans to determine the number of clusters and classify the data. After cleaning and changing to numeric, the data was transformed to “primary component” data frame with PC1,2,3. Then PC data frame was used to determine the clusters. 
•	The number of clusters was determined by using elbow curve. Based on the curve the number of clusters was set as 4 as the difference of data variability (interia) between 3 and 4 clusters model is x10^6, whereas between 4 and 5 clusters it is x1.5.
•	After Processing and grouping I plotted the data using hvplots.  3D scatter plot clearly shows 4x distinguishable clusters. 2D scatter plot of Total Coins Mined vs Total Coins supply, does not resolve clusters clearly. The log version of 2D plot shows that group 3 has Total Coins supply ~0 and groups 0 and 1 of the groups vary from 0 to 10^12 and group 2 is 10^12 only. *Balanced accuracy score (F1): measures the accuracy of how often the classifier is correct with the model weighing each class. It is combination of precision and recall (or precision of true positive and precision of true negative).
 
## Resources

- Technologies used: Python, sklearn package,  KMeans
- Programs: crypto_currency_challenge.ipynb
- Resources: Resources/ crypto_data.csv
- User must download crypto_currency_challenge file and Resources folder to the same location

