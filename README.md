# netflix-data-analysis
This is a personal project I did to practice some Data Analytics skills.  
Dataset comes from kaggle. I do not own the dataset. https://www.kaggle.com/datasets/shivamb/netflix-shows  
Dataset is about Netflix shows. Netflix is an American subscription video on-demand over-the-top streaming service. The service primarily distributes original and acquired films and television shows from various genres, and it is available internationally in multiple languages.  
Dataset is in a CSV file format. It contains shows that are/were available in Netflix and contains 8807 records and 12 attributes.  
Attributes: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description  

Dataset normalized into tables:
- shows (show_id, type, title, date_added, release_year, rating_id, description)
- directors (director_id, director_name)
- casts (cast_id, cast_name)
- categories (category_id, category_name)
- countries (country_id, country_name)
- ratings (rating_id, rating_name)
- movie_duration (movie_duration_id, show_id, minutes)
- tv_show_duration (tv_show_duration_id, show_id, seasons)
- show_directors (show_id, director_id)
- show_casts (show_id, cast_id)
- show_category (show_id, category_id)
- show_countries (show_id, country_id)

Loaded to MySQL database in my machine and also saved in CSV files.  
Dashboard visualization via PowerBI.  

![image](https://github.com/arceldizon28/netflix-data-analysis/assets/148745972/c16bd865-ba49-4f1d-b4cf-7bbf6af6f8e3)
![image](https://github.com/arceldizon28/netflix-data-analysis/assets/148745972/a57c618a-47ae-48de-af7c-0cdb8533829d)
![image](https://github.com/arceldizon28/netflix-data-analysis/assets/148745972/56d56ca6-865e-4fe9-9858-45db617ba6fa)
![image](https://github.com/arceldizon28/netflix-data-analysis/assets/148745972/faff2358-96db-4df1-aa58-50c5523f75c1)
![image](https://github.com/arceldizon28/netflix-data-analysis/assets/148745972/751f951f-13c9-4442-98e8-d70d53ccb138)


