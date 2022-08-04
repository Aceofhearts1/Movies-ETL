# Movies-ETL

## Brief summary
The goal was to create an automated pipeline that takes in new data. The code performs the ETL process and uploads in to the PostgreSQL database.

1. With the extracted data we see there are come issues with it. It has to be cleaned.
2. We load in the extracted data as Dataframes. They are easy to clean. We transform the data by filling in numbers, dropping tables, zeroing useless data, and creating Ids through regular expression and more.
3. Lastly, we send the data to our PgAdmin Database.
![Link](https://github.com/Aceofhearts1/Movies-ETL/blob/main/Resources/movies_query.png)
![](https://github.com/Aceofhearts1/Movies-ETL/blob/main/Resources/ratings_query.png)
![](https://github.com/Aceofhearts1/Movies-ETL/blob/main/Resources/movie_database.png)
![](https://github.com/Aceofhearts1/Movies-ETL/blob/main/Resources/movie_database2.png)
