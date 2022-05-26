<h1 align="center"><b>Dastaan</b></h1>
<p align="center">
</p>


## INTRODUCTION:
    Dastaan- 'don't wait, watch it right away' , is a web development project made under Microsft Engage Program 2022.It's always been a problem searching for the movies similar to your favorites, Right?.You had to go to Google ,search for the reviews,search for the genre then repeat the cycle again and again.So, What you gotta do is, come at Dastaan and get your problem solved. You enter any movie , and we get you the list of movies similar to the one you entered.This is acheived using content-based filter and text-mining from the reviews we fetch from IMDB . 



## Demo Video Link:
  

## Table of Contents:
* [ How to run the project? ](#how_to)
* [ Features ](#features)
* [ Tech Stack ](#technologystack)
* [ Workflow  ](#models) 
* [ Future Plans ](#futureplans)
* [ Limitations ](#limitations)
* [ Images ](#images)
* [ Credits ](#credits)



## <a name="how_to"></a>How to run the project?
1) Clone this repository on your system.
2) Install all the requirements mentioned in [requirements.txt](https://github.com/Simran-Valecha/dastaan-2022/blob/master/requirements.txt) by typing `pip install -r requirements.txt` on your terminal.
3) Also, don't forget to get your API key from https://www.themoviedb.org/. .
4) Replace my api key with yours in **both** the places (line no. 16 and 30) of `static/recommend.js` file .
5) Save all the changes.
6) Run the file `main.py` by executing the command `python main.py`.
7) Here begins the dastaan.

## <a name="features"></a>Features :
1)Autocomplete- While searching for the movie,you are automatically suggested to fill it.
2)Unveil movie details-The name of the movie, genre, release date,overview, poster card are fetched from the api and displayed beautifully.
3)Movie cast- Top 10 cast of the movie is showcased with their original name and the name of the character in the movie.
4)Poster Card- You can click on 'Know More' to get to know more about your favourite cast,
5)Suggest similar movies- Display top 10 Recommended movies based on sentiments analysis
6)Reviews fetched from IMDB api are displayed on which sentiment analysis is done. 



## <a name="technologystack"></a>Tech Stack:
  -Python(Flask)
  -HTML
  -CSS
  -JavaScript(JQuery)
  -Bootstrap
  -Jupyter Notebook


## <a name="models"></a>Workflow:

 
 ## <a name="futureplans"></a>Future Plans:
 * Maintain the wishlist of the users.
 * Try and implement collaborative filtering based recommender.
 * Collect the votes to calculate the success rate of our movie recommender


  ## <a name="limitaions"></a>Limitations:
* This website is tested only in Google Chrome and is compatible with it
* Tested only on laptop and not on mobile phones



## <a name="images"></a>Images:


## <a name="credits"></a>Credits:
* I owe a big part of this project to Mr. Rohit Kumar Shaw, my mentor for Microsoft-Engage-2022.
* Developer - [Simran Valecha](https://github.com/Simran-Valecha)



