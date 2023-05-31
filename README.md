# Movie Website with React JS

This project is a movie website called "Myflix" that allows users to search for movies and view popular movies. The movie data is retrieved from the database provided by The Movie Database (TMDb).

## Setup

To set up the project locally, follow these steps:

1. Clone the repository or download the source code.
2. Install the necessary dependencies by running the following command in the project directory:
3. Create an account on [The Movie Database](https://www.themoviedb.org/) and obtain an API key.
4. Create a file named `.env` in the project directory and add the following line, replacing `YOUR_API_KEY` with your actual API key:
5. Start the development server by running the following command:


This will start the application on `http://localhost:3000` by default.

## Functionality

The Myflix website provides the following functionality:

- **Movie Search**: Users can enter a movie title in the search bar to search for movies. The search is triggered after typing more than 3 characters. The search results are displayed dynamically as the user types.

- **Popular Movie List**: The website displays a list of popular movies by default. The list is fetched from the TMDb database and is updated upon the initial loading of the website. Each movie in the list is displayed with its title, release date, average vote rating, and a poster image.
