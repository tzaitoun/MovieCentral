# MovieCentral
An Android client for the TMDb that utilizes movie data to give users a place to view movie information and stay informed using the News API.

The application has 3 main functions: viewing movies, viewing news about movies, and searching for movies.

## Authentication 
Since this is a client for TMDb, I authenticate the user using TMDb.The user has to have a TMDb account to use the application. The image below illustrates the sign in/up process, after a user is signed in they will be redirected to the movie screen in the second image below. The user's session will only be invalidated if they sign out.

<img src="https://github.com/tzaitoun/MovieCentral/blob/master/Authentication.png" width="600"></img>

## View Movies 
The user is able to view movies from the movie screen for Popular, Playing Now, Upcoming, and their Watchlist. They will be able to look at a larger selection by clicking more (this screen uses paging to display all movies in that category from the api) and view details of a movie by clicking on it. In the details page, the user can add a movie to their watchlist, rate a movie, view movie information, and reviews.

<img src="https://github.com/tzaitoun/MovieCentral/blob/master/MovieScreen.png" width="600"></img>

## View News 
The user can view news about movies from the past week and click on it to read the article in the browser.

<img src="https://github.com/tzaitoun/MovieCentral/blob/master/NewsFeed.png" width="400"></img>

## Searching for movies (Not Done Yet)
The user will be able to search for movies and their search history will be cached. What the user can search for will depend on the capability of the api.

## Libraries used so far
- Retrofit
- RxJava
- Custom Chrome Tabs
- Picasso
- https://github.com/lopspower/CircularProgressBar
- https://github.com/amulyakhare/TextDrawable
