# cryptocurrencies

## Project Overview:

Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, she created a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

## Results:
1) By using Pandas, we preprocess the crypto dataset in order to perform PCA.
 
![2022-05-07](https://user-images.githubusercontent.com/96403349/167263925-9e706504-6cba-4e14-adf0-55acc2bc5485.png)


2) By using Principal Component Analysis (PCA) algorithm, reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

![2022-05-07 (1)](https://user-images.githubusercontent.com/96403349/167263979-1fab3f2e-4e3a-45e9-bd97-e370ffe975a8.png)


3) By using K-means algorithm, created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame ( columns, PC 1, PC 2, and PC 3). Then, ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

![2022-05-07 (2)](https://user-images.githubusercontent.com/96403349/167264220-b2d6fcbb-4c8f-47c1-8e47-6994414ef6cb.png)

4) By using scatter plots with Plotly Express and hvplot, visualized the distinct groups that correspond to the three principal components and created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

![2022-05-07 (3)](https://user-images.githubusercontent.com/96403349/167264350-49b5f2ed-6f72-4dd0-a27b-28bf6fa31423.png)

## Summary:
This project focused on unsupervised learning and used hvplot, Pandas, and jupyter notebook to process and cluster cryptocurrency data. The analysis was conducted in four main steps how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principal components using PCA. 






 

