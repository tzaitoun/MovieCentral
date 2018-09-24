# MovieCentral - In Progress (Educational)
An Android client for the tMDB that utilizes movie data to give users a place to view movie information, discuss movies and stay informed using the News API.

The purpose of this application is to allow me to build a more complex application on the Android platform and along the way learn new concepts/libraries/patterns. I'am hoping to learn more about the following: RxJava, Retrofit, Animations, UI Design and layouts, supporting multiple screens, UI testing, and unit testing.

<img src="https://github.com/tzaitoun/MovieCentral/blob/master/Authentication.png" width="600"></img>

Since this is a client for tMDB, I authenticate the user using tMDB.The user has to have a tMDB account to use the application (atleast for now). The image above illustrates the sign in/up process, after a user is signed in they will be redirected to the first screen in the image below. The user's session will only be invalidated if they sign out (tMDB session id's never expire).

The application has 4 main functions: viewing movies, viewing news about movies, searching for movies, and talking about movies (movie discussion boards). Currently, I have only done work on the first two.

## View Movies 
The user will be able to view movies from the movie screen for Popular, Playing Now, Upcoming, etc sorts by most popular by default. They will be able to look at a larger selection by clicking more (this screen uses paging to display all movies in that category from the api) and view details of a movie by clicking on it. In the details page, the user will be able to add a movie to their watchlist, rate a movie, view movie information, and reviews. More things will be added to this page to integrate the other parts of the application with it.

<img src="https://github.com/tzaitoun/MovieCentral/blob/master/MovieScreen.png" width="600"></img>

## View News 
The user can view news about movies from the past week and click on it to read the article in the browser.

<img src="https://github.com/tzaitoun/MovieCentral/blob/master/NewsFeed.png" width="400"></img>

## Searching for movies 
The user will be able to search for movies and their search history will be cached. What the user can search for will depend on the capability of the api.

## Talking about movies
The users will be able to create new posts on a movie's discussion board. 

## Libraries used so far
- Retrofit
- RxJava
- Epoxy (RecyclerView)
- Picasso
- RxFirebase
- https://github.com/lopspower/CircularProgressBar
- https://github.com/amulyakhare/TextDrawable
