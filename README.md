# ETL-Project

Extraction

We used 3 datasets from the public platform Kaggle and Data World. All of our data was based on county through all the States ranging over various years from 2010 to 2015. These were the most recent ones we could find. The sources for our dataset are as follows
 
•	Diversity Index from Kaggle.
•	Unemployment from Kaggle.
•	Median Income by county from Data World.

Transformation

Our first steps in cleaning up the datasets involved figuring out which variables were not relevant. 

Load

The last step was to transfer our final output into a Database. We created a database and respective tables to match the columns from the final Panda’s Data Frame using MYSQL and then connected to the database using SQLAlchemy and loaded the result. 
