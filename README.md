# Movie Recommendation App

The Movie Recommendation App is a web application that allows users to manage their favorite movies, get personalized movie recommendations using ChatGPT, and access contact and support information. This repository contains both the backend and frontend code, providing a complete movie management and recommendation system.

## Code Structure Organization

The code is organized into two main directories: `backend` and `frontend`.

### Backend

- **config/database.js:** This file contains the configuration settings for the database used by the application.

- **models/Movie.js:** The `Movie` model defines the schema for storing movie data in the database.

- **routes.js:** The `routes.js` file defines the API routes and their corresponding request handlers.

- **server.js:** The `server.js` file serves as the entry point for the backend application, starting the server and connecting to the database.

### Frontend

The `frontend` directory contains various components and features that make up the user interface of the Movie Recommendation App:

- **src/components/AddMovies.js:** This component allows users to add new movies to their list of favorite movies.

- **src/components/Contacts.js:** Here, users can find contact and support information for the application.

- **src/components/Favorites.js:** Users can manage their list of favorite movies using this component.

- **src/components/Home.js:** The landing page for the Movie Recommendation App provides an introduction and overview of the application.

- **src/components/Recommendations.js:** This component generates ChatGPT prompts and allows users to copy the generated statements for movie recommendations.

- **src/api/api.js:** The `api.js` file handles communication between the frontend and backend servers.

- **App.js:** The `App.js` file defines the overall structure of the movie recommendation app, including navigation links to different app sections.

## Getting Started

To run the Movie Recommendation App locally, follow these steps:

1. Clone this repository to your local machine.

2. Navigate to the `backend` directory and install the required dependencies by running `npm install`.

3. Start the backend server by running `npm start`.

4. Open a new terminal window, navigate to the `frontend` directory, and install the required dependencies by running `npm install`.

5. Start the frontend development server by running `npm start`.

6. Access the application in your web browser at `http://localhost:3000`.