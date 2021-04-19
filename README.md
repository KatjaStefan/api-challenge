## API Challenge

### Instructions
We want to get lists of movies! Use the URL below to do 2 API calls, with different parameters, and follow the instructions below on what the output should look like.
Feel free to use any other HTTP request library than the suggested in the challenges.
URL: https://jsonmock.hackerrank.com/api/movies/search/?Title=_SEARCHTERM_
(Hint replace the _SEARCHTERM_ text in the url)

### Output format
Combine the results of the 2 API calls, and map them into the following JSON structure:
  {
    substrA: [
      { title: title - year, imdbID },
      { title: title - year, imdbID },
      { title: title - year, imdbID },
    ],
    substrB: [
      { title: title - year, imdbID },
      { title: title - year, imdbID },
      { title: title - year, imdbID },
    ]
  }
Print the mapped JSON result to the console

### Example Input
Substring input 1: Deathly
Substring input 2: Goblet

### Example Output
  {
    Deathly: [
      { title: 'Harry Potter and the Deathly Hallows: Part 1 - 2010', imdbID: 65573 },
      { title: 'Harry Potter and the Deathly Hallows: Part 2 - 2011', imdbID: 62234 }
    ],
    Goblet: [
      { title: 'Harry Potter and the Goblet of Fire - 2005', imdbID: 12351 },
      { title: 'Inside 'Harry Potter and the Goblet of Fire' - 2005", imdbID: 34564 }
    ]
  }
