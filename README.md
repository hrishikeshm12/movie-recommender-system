# movie-recommender-system
 This is a python project for simulating a movie recommender system based on a movie given as a choice by the user.The data set used in this project was the TMD 5000 movies dataset.
 
 The approach to this project is given below:
    1. Jupyter Notebooks was used to perform exploratory data analysis, data cleaning, missing value validation as well as other data manipulation methods.
    2. After performing these steps the movie tags were generated which were a combination of actor, director, genre, as well as tags specific to each movie.
    3. Different functions were defined to calculate the similarity score between 2 particular movies using the concept of String Vectorization which convert a string to a vector in n dimensional vector space.
    4. After generating the individual arrays for each movie the next step was to calculate the similariy between 2 movies. This approach was based on the fact that to find the similairties betwwen any two movies we see the distance between the two movie vectors that were generated previously. The distance was not regular Eucleadian distance which we use frequenlty but the cosine distance.
    5. The distance between a movie and all other movies was calculated and stored in a matrix.
    6. In the next step we sort out the top 5 movies having the highest similairty index and then recommend it to the user.
    7. For the web application part we take a movie from the user and recommend him top 5 movies to him.
    8. The posters for each movie was made available using the TMDB movie API which when provided with a movie_id returns a image of the particular movie.
   
   
Requirements for this project are :
  1. Jupyter Noteebok
  2. Pycharm
  3. TMDB account

The live deployment of this project can be found at : https://movie-recommender-hrishikesh.herokuapp.com

![image](https://user-images.githubusercontent.com/65590350/173230440-85f44876-3c60-4e66-a9af-e7e03048d7d2.png)

