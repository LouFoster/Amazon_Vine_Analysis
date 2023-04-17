# Amazon_Vine_Analysis

Deliverable 1: Perform ETL on Amazon Product Reviews (40 points)

Using your knowledge of the cloud ETL process, you’ll create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets, and extract the dataset into a DataFrame.

Deliverable 2: Determine Bias of Vine Reviews (40 points)

Deliverable 3: A Written Report on the Analysis (20 points)

Deliverable 3: A Written Report on the Analysis (20 points)



##Deliverable 1: Perform ETL on Amazon Product Reviews (40 points)

2.	Create a new database with Amazon RDS just as you did in this module.

3.	In pgAdmin, create a new database in your Amazon RDS server that you just create.

![image](https://user-images.githubusercontent.com/117233641/232491344-f6ebbc9e-46fa-4073-8d8e-773dc2c7f490.png)

4.	Download the challenge_schema.sql file to your computer.

5.	In pgAdmin, run a new query to create the tables for your new database using the code from the challenge_schema.sql file.
  o	After you run the query, you should have the following four tables in your database: customers_table, products_table, review_id_table, and vine_table.

![image](https://user-images.githubusercontent.com/117233641/232491611-b143a11d-fb8a-487b-81a4-29351a962160.png)

7.	Download the Amazon_Reviews_ETL_starter_code.ipynb file, then upload the file as a Google Colab Notebook, and rename it Amazon_Reviews_ETL.


8.	First extract one of the review datasets, then create a new DataFrame.

![image](https://user-images.githubusercontent.com/117233641/232491692-adb20561-eedc-451e-944e-a6b44030fd33.png)

Next, follow the steps below to transform the dataset into four DataFrames that will match the schema in the pgAdmin tables:
