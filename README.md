# Myflix Movie Website 
This project is a movie website called "Myflix" that allows users to search for movies and view popular movies. The movie data is retrieved from the database provided by The Movie Database (TMDb).

### Setup
To set up the project locally, follow these steps:

Clone the repository or download the source code.

Install the necessary dependencies by running the following command in the project directory:

Copy code
npm install
Create an account on The Movie Database and obtain an API key.

Create a file named .env in the project directory and add the following line, replacing YOUR_API_KEY with your actual API key:

makefile
Copy code
REACT_APP_API_KEY=YOUR_API_KEY
Start the development server by running the following command:

sql
Copy code
npm start
This will start the application on http://localhost:3000 by default.

### Functionality
The Myflix website provides the following functionality:

Movie Search: Users can enter a movie title in the search bar to search for movies. The search is triggered after typing more than 3 characters. The search results are displayed dynamically as the user types.

Popular Movie List: The website displays a list of popular movies by default. The list is fetched from the TMDb database and is updated upon the initial loading of the website. Each movie in the list is displayed with its title, release date, average vote rating, and a poster image.
