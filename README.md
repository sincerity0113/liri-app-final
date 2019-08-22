# liri-node-app

Language Interpretation and Recognition Interface (or LIRI for short) is a command line node app that searches Spotify for songs, Bands in Town for concerts, and OMDB for movies. Inquirer is used to simplify user input while Node-Spotify-API and Axios are used to submit API requests.

Requirements
  Node.js LTS (v10)


Dependencies
  Inquirer
  Node-Spotify-API
  Axios
  Moment
  DotEnv
  Chalk

How to
Upon launch, LIRI will prompt you to select a search category. The options are:

Search Spotify
When selecting this option, you will get another prompt to select search by song, album or artist
Once a selection has been made, input a search term and hit enter
Find upcoming concerts
Input an artist/band to see the venue, location and time of the next concert
Get information about a movie
Enter a movie search term to see ratings, movie details and a plot summary
Do something at random
This selection is dependent on the content of the 'random.txt' file. The file must contain one of the following key words:
song OR concert OR movie (excluding quotes)
The default is set to 'movie' - which will initiate a movie search
To initiate new search  

Test screen
![testimg](https://i.imgur.com/x5bd8gu.gif)

Author
Taeyeong(T.J.) Park
