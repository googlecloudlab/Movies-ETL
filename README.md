# Movies-ETL

## Overview
Amazing Prime wants to keep it's dataset updated on a daily basis. I will create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I will refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Deliverables
*Deliverable 1: Write an ETL Function to Read Three Data Files*
Using my knowledge of Python, Pandas, the ETL process, and code refactoring, I write a function that reads in the three data files and creates three separate DataFrames.

*Deliverable 2: Extract and Transform the Wikipedia Data*
Using my knowledge of Python, Pandas, the ETL process, and code refactoring, I extract and transform the Wikipedia data so I can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, I use a try-except block to catch errors.

*Deliverable 3: Extract and Transform the Kaggle data*
Using my knowledge of Python, Pandas, the ETL process, and code refactoring, I extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, I merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, I merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

*Deliverable 4: Create the Movie Database*
I use my knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
