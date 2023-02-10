# spring-movies-api
## Run on your system
1. Clone the repo
2. Open the terminal
3. Navigate to the path of the repo where you cloned it
4. Go to ```SpringMoviesApiApplication.java``` and run it
5. Done! Now you can try the endpoints below using a client such as Postman or Thunder Client

## Endpoints
* Get all movies: ``` GET localhost:8080/api/v1/movies```
* Get a movie by IMDB ID: ```GET localhost:8080/api/v1/movies/:imdbId```
* Create a review, make sure to include the IMDB ID: ```localhost:8080/api/v1/review```
  * Request body: 
  ```
  {
    "imdbId": string,
    "reviewBody: string
  }
  ```
