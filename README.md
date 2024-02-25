# Movie Trailer Search App

## Overview
This is a simple web application that allows users to search for movie or web series trailers using the Movie Trailer API. Users can input the name of the movie or web series they are interested in, and the application will fetch the corresponding trailer from the internet and display it on the webpage.

## Prerequisites
Before running the application, ensure you have the following installed:

- React
- React Hooks
- JavaScript ES6
- React Axios & API
- Functional Components

## Approach
The application consists of two main sections:
1. **Input Section:** This section allows users to input the name of the movie or web series they want to search for.
2. **Video Display Section:** Here, the fetched trailer will be displayed.

When a user searches for a video, the application will store the user input inside a state variable. Upon clicking the search button, a function will be called to fetch the required video URL using the `movie-trailer` package and store it in another state variable. Once the URL is obtained, the video will be rendered using the `ReactPlayer` component.

## Project Setup
Follow these steps to set up the project:

### Step 1: Create React App
Create a new React application using the following command:
```bash
npx create-react-app movie-app
```

### Step 2: Navigate to Project Folder
Move to the project folder by running:
```bash
cd movie-app
```

### Step 3: Install Required Packages
Install the necessary npm packages for the project:
```bash
npm install movie-trailer
npm install react-player
```

## Usage
1. After setting up the project, run the application using:
   ```bash
   npm start
   ```
2. Open your web browser and navigate to `http://localhost:3000`.
3. Enter the name of the movie or web series you want to search for in the input field.
4. Click on the search button.
5. The trailer corresponding to the entered search query will be displayed on the webpage.


## License
This project is licensed under the [MIT License](LICENSE).
