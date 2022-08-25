# Assembling_investment_portfolios
## Crypto_Clustering-Kmeans-PCA
 
 In this Module ML algo is combination between Python and unsupervised learing.
 One CVS file provides crypto dataset
 ![Screenshot 2022-08-24 221903](https://user-images.githubusercontent.com/69637182/186573966-89358834-077f-4bfd-aaa2-31a6e33f70b5.png)
 ![bokeh_plot](https://user-images.githubusercontent.com/69637182/186573949-560ec506-173b-4103-9b72-09ea8d7315cc.png)
 The resolve this challenge we need to follow these steps:
 ![Screenshot 2022-08-24 222036](https://user-images.githubusercontent.com/69637182/186573971-f3c386b9-d77d-4416-9b2a-52d25c4195ec.png)
 Import the Data,Prepare the Data, find the best Kmeans with original Data, minimize Data by using Principal component Analysis then the best   K using PCA Data Clusters.
 at the end Visualize and compare the results
 
 # Import The Data
In this part we import different libraries, then read CSV file, set index_col to 'coin_id' after we got a new DataFrame.
 apply info, describe methods to see how Data distributed after with hvplot to plot and visualize our new DataFrame



![Screenshot 2022-08-24 222134](https://user-images.githubusercontent.com/69637182/186573980-cf03ef1f-52aa-4df3-a59a-066f7a934379.png)


## Prepare the Data
 
 by eye balling the describe method, the Data isn't evenly distributed so I had to scale it by using StandardScaler module, fit_tranform 
 Data.
 
 ## kmeans
 
 By using elbow method for finding the best k: for loop 1 to 11.
 
 Plot line chart with all inertia value
 
 Answer the following question: What is the best value for k?

Question: What is the best value for k?

Answer: 4

## Kpca

By using elbow method for finding the best k: for loop 1 to 11.
 
 Plot line chart with all inertia value
 
 Question: What is the best value for k when using the PCA data?

Answer: 4 Question: Does it differ from the best k value found using the original data?

Answer: No, the best k value does not change. However, 4 has dropped 25 points on the inertia scale.
![Screenshot 2022-08-24 222233](https://user-images.githubusercontent.com/69637182/186573986-fd90db2f-f1ef-4824-bbca-654a49fa8c73.png)
![Screenshot 2022-08-24 222258](https://user-images.githubusercontent.com/69637182/186573998-ca01e168-8373-4ce0-b099-178e2dcc8de6.png)
