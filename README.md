Live Server - https://movie-recommendation-chitramaya.netlify.app/

ChitraMaya - Movie Discovery Web Application
ChitraMaya is a simple web application designed to help users discover movies based on their preferences. Users can search for movies by title, filter by genre and rating, and view detailed information about each movie, including recommendations for similar movies.

Features
Search and Filter: Users can search for movies by title and filter results by genre and rating.

Movie Details: Clicking on a movie card opens a detailed view with information such as the movie's title, genre, rating, director, year, description, and image.

Recommendations: Based on the selected movie, the application suggests similar movies from the same genre and with a similar rating.

Responsive Design: The application is designed to be responsive and accessible on various devices.

Technologies Used
HTML: Structure of the web pages.

CSS: Styling and layout of the application.

JavaScript: Dynamic functionality, including filtering, displaying movies, and handling user interactions.

JSON: Data storage for movie information.

File Structure
index.html: The main page where users can search and filter movies.

moviePage.html: The page displaying detailed information about a selected movie and recommendations.

data.js: Contains the movie data in JSON format.

script.js: Handles the main functionality, including displaying movies, filtering, and navigating to the movie details page.

movieDetails.js: Handles the display of movie details and recommendations on the movie details page.

style.css: Contains the styles for the application.

How to Use
Search and Filter Movies:

On the main page (index.html), use the search bar to find movies by title.

Use the genre and rating dropdowns to filter movies by genre and minimum rating.

View Movie Details:

Click on any movie card to open the movie details page (moviePage.html).

The details page will display information about the selected movie and provide recommendations for similar movies.

Navigate Back:

Use the "Home" link in the navigation bar to return to the main page.

Example Data
The movie data is stored in data.js and includes the following fields for each movie:

title: The title of the movie.

genre: The genre of the movie (e.g., Action, Comedy, Drama, Scientific).

rating: The movie's rating (out of 10).

director: The director of the movie.

year: The year the movie was released.

description: A brief description of the movie.

image: A URL to the movie's poster image.
