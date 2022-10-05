# Movielens-Case-Study
DESCRIPTION

Background of Problem Statement :

Movie data contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000. Data set also contain movie Genres(ex. action, advanture, comedy etc.) and occupation of reviewer(ex. doctor, lawyer etc.)


Problem Objective :

Here, we ask you to perform the analysis using the Exploratory Data Analysis technique. You need to find features affecting the ratings of any particular movie and build a model to predict the movie ratings. Do data visulization and plot graphs like top 25 movies, user age distribution etc.


Domain: Entertainment


Files:

Ratings.dat
    Format - UserID::MovieID::Rating::Timestamp

Field	Description
UserID	Unique identification for each user(range between 1 and 6040 )
MovieID	Unique identification for each movie
Rating	User rating for each movie(Ratings are made on a 5-star scale)
Timestamp	Timestamp generated while adding user review (A timestamp is represented in seconds since the epoch is returned by time(2))

Each user has at least 20 ratings


Users.dat
Format -  UserID::Gender::Age::Occupation::Zip-code

Field	Description
UserID	Unique identification for each user
Gender	Gender(M or F)
Age	User’s age
Occupation	User’s Occupation
Zip-code	Zip Code for the user’s location


Movies.dat
Format - MovieID::Title::Genres

Field	Description
MovieID	Unique identification for each movie
Title	A title for each movie
Genres	Category of each movie
