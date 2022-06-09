Steps to Run Project
Our Project we have basically divided into 4 section
1. Data Cleaning (on GoogleColab)
2. EDA (In Databricks)
3. Machine Learning (In Databricks)
4. Word2Vec (In Databricks)

Part 1 - Data Cleaning (on GoogleColab)
Steps
(1) Upload 603_DataCleaning.ipynb file in Google Colab.
(2) Upload the 'GooglePlaystoreData.csv' in the same Colab notebook
	(It will take time to upload due to the size)
(3) Run the notebook. It will generate a csv named 'GooglePlayStore.csv' of cleaned data

Before moving on to the second part, 
We have used Databricks community free edition for our project.
In order to access the community edition sign in to the link -'https://community.cloud.databricks.com/'

Part 2,3 and 4 - In Databricks
(1) In the Data tab in Databricks create table and upload the clead data i.e. 'GooglePlayStore.csv'.
(2) Similarly import the 'GoogleReviews.csv' into Databricks
(3) Import the notebooks 603_EDA.dbc, 603_SparkMLlib.dbc, 603_Word2Vec.dbc into the workspace in databricks
(4) Create a cluster in the workspace where you will be executing the .dbc notebook
(5) Run the notebooks on the created cluster.