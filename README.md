# Movies-ETL
**MODULE 8 Challenge**

**Movie Data Cleanup**

This challenge is all about cleaning the raw database and then merging the tables to get most relevant data and loading them into database. For this we have given 3 data files (Wikipedia data, Kaggle metadata, and the MovieLens rating data), we converted them to dataframe and then performed the cleanup using regex expressions by creating functions.

- First we **Extracted** the database and convert them in to dataframe (wiki\_movies\_df, kaggle\_metadata, ratings)
- Then, we **Transformed** the datasets by cleaning them up using regex,dropna,changing data types and then joining them together (movies\_df, movies\_with\_ratings\_df)
- At last, we **Load** the cleaned dataset into SQL database (movie\_data) into two tables (movies and ratings)