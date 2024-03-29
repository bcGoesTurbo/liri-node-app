# liri-node-app
Week 10 (LIRI Bot) Assignment

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in one of four parameters and gives you back data.

## Prerequisites
```
- Node.js - Download the latest version of Node https://nodejs.org/en/
```
## Getting Started

- Clone down repo.
- Run command 'npm install' in Terminal or GitBash
- Run command 'node liri.js' with one of the commands below, then add search text:

  * `concert-this`    

  * `spotify-this-song`

  * `movie-this`

  * `do-what-it-says`

### When running a command follow it by desired text/search.
Example:
node liri.js movie-this inception

## What Each Command Does

1. `node liri.js concert-this <artist/band name here>`

  * This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

     * Name of the venue
     * Venue location
     * Date of the Event (use moment to format this as "MM/DD/YYYY").

2. `node liri.js spotify-this-song <song name>`

* This will show the following information about the song in your terminal/bash window

    * Artist(s)
    * The song's name
    * A preview link of the song from Spotify
    * The album that the song is from
    * If no song is provided then your program will default to "The Sign" by Ace of Base.

3. `node liri.js movie-this <movie name>`

  * Shows the following information in terminal/bash.

    * Title of the movie.
    * Year the movie came out.
    * IMDB Rating of the movie.
    * Country where the movie was produced.
    * Language of the movie.
    * Plot of the movie.
    * Actors in the movie.
    * Rotten Tomatoes Rating.
    * Rotten Tomatoes URL.

  * Or if no movie is passed through, it will default to "Mr. Nobody"

4. `node liri.js do-what-it-says`

  * Takes the text from random.txt and runs the song through spotify-this-song command
    
## Author

* **Brad Cook** 


