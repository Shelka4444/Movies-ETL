# Movies ETL
Creating a new database for movies using ETL processes with JSON, Pandas, PostgreSQL, and pgAdmin.

Three files— Wikipedia data, Kaggle metadata, and the MovieLens rating data - are extracted from their respective online sources, tranformed into clean, usable data, and then loaded to a PostgreSQL database. After extracting and transforming the data, Wikipedia and Kaggle metadata were merged into one dataframe to create movies_df. MovieLens rating data was then added on to movies_df to create movies_with_ratings_df. A timestamp was added to the code to monitor the progress of transfering the stored dataframes into PostgreSQL. The database contains two tables (movies and ratings) with the cleaned data as confirmed by the queries below: 

<p align="center">
<img src="https://github.com/Shelka4444/Movies-ETL/blob/main/Resources/movies_query.png" alt="Movies Query" width="300"> 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://github.com/Shelka4444/Movies-ETL/blob/main/Resources/ratings_query.png" alt="Ratings Query" width="300">
</p>                                                                                                                         
