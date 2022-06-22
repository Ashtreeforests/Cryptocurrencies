# Cryptocurrencies

## Objective: 

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked for a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data set is not ideal, so it will need to be processed to fit the machine learning models. Methodology for this research and report is considered to be unsupervised learning as there is no known output. A clustering algorithm was used to group the cryptocurrencies. Data visualizations were used to share the findings.

## Results: 

### Clusters
The optimal number of clusters is 4 based on the below elbow curve. 
![image](https://user-images.githubusercontent.com/96931376/174917353-b52fd1d1-8720-4384-bfc7-dddc5ec4e7e2.png)

### hvTable
The hvTable below displays all of the currently tradeable cryptocurrencies. 
![image](https://user-images.githubusercontent.com/96931376/174917636-9e942a3e-ea9e-4b17-82b5-435cafc58b6b.png)

### Scatter Plots
Distribution and the 4 clusters of cryptocurrencies are shown with the below 3D and 2D scatter plots.

#### 3D scatter plot
The below 3-D scatter plot was created using the PCA algorithm, which reduced the crytocurrencies dimensions to three principal components.
![image](https://user-images.githubusercontent.com/96931376/174917475-04f59dde-2df1-44aa-bbf3-7cee7a350c11.png)

#### 2D scatter plot 
The hvPlot is a scatter plot graph grouped by class. The below 2-D scatter plot was created using the PCA algorithm, which reduced the crytocurrencies dimensions to two principal components.
![image](https://user-images.githubusercontent.com/96931376/174917718-a293d390-2c2e-4a86-b1c5-a56397af6f80.png)

## Summary: 

532 cryptocurrencies were identified and classified based on similarities of their features. Additional studies are required to determine each group's performance and potential as an investment.
