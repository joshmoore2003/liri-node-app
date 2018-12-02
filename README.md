# liri-node-app
Week 10 (LIRI Bot) Assignment

The goal was to use Node JS to create a LIRI bot, like iPhone's SIRI, but takes in command through Language vs Speech. LIRI is a command line node app that takes in parameters and returns data based on one of four commands:

  * `spotify-this-song`

  * `movie-this`

  * `concert-this`

  * `do-what-it-says`

## Getting Started

- Clone down repo to local computer.
- Install all dependencies by going to the terminal and typing `npm install`
- Setup a .env file on your local desktop that contains all of your API Keys necessary to run the app.
- Run command 'node liri.js' followed by one of the commands listed.
    - `spotify-this-song`
    - `movie-this`
    - `do-what-it-says`

## What Each Command Does


1. `node liri.js spotify-this-song <song name>`

  * Shows the following information about the song in terminal/bash window.
    * Artist(s)
    * The song's name
    * A preview link of the song from Spotify
    * The album that the song is from

  * If no song is provided, then the program will default to
    * "The Sign" by Ace of Base

2. `node liri.js movie-this <movie name>`

  * Shows the following information in terminal/bash.

    * Title of the movie.
    * Year the movie came out.
    * IMDB Rating of the movie.
    * Rotten Tomatoes Rating of the movie.
    * Country where the movie was produced.
    * Language of the movie.
    * Plot of the movie.
    * Actors in the movie.

  * Or if no movie is passed through, it will default to "Mr. Nobody"

3. `node liri.js concert-this`

  * This will search the Bands in Town Artist Events API and render the following information about each event to the terminal
    * Name of the venue
    * Venue location
    * Date of teh Event (using moment to formate it as "MM/DD/YYY")

4. `node liri.js do-what-it-says`

  * Takes the text from random.txt and runs the song through spotify-this-song, the movie through movie-this and the artist through concert-this commands

## Tech used
- Node.js
- Node-Spotify-API NPM Package - https://www.npmjs.com/package/node-spotify-api
- Request NPM Package - https://www.npmjs.com/package/request
- Moment NPM Package - https://www.npmjs.com/package/moment
- DotEnv Package - https://www.npmjs.com/package/dotenv
- OMDB API - http://www.omdbapi.com/
- Bands In Town API - http://www.artists.bandsintown.com/bandsintown-api

## Prerequisites
```
- Node.js - Download the latest version of Node https://nodejs.org/en/
```

## Built With

* Visula Studio Code

## Author

* **Joshua Moore** - *Node JS* - [Joshua Moore](https://github.com/joshmoore2003)