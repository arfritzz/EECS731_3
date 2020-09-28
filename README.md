### EECS 731 Project 3

#### Goal 

The goal of this project was to use feature engineering and a clustering alogrithm to find movies in a similar cluster. One could then recommend other movies in that cluster based on the movies title. 

#### Findings 

In the notebook `clustering_report` I used KMeans clustering with 10 clusters to develop a model to group movies with similar ratings and polarity of tags (ie negativity or positivity of tags). I chose 10 clusters based on the elbow method. The final product is the `recommend` function which recommends similar titles based on the cluster. 
