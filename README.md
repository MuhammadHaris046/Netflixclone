This is a personal project I built to strengthen my skills in frontend development using React and Firebase. The goal was to replicate the core functionality of Netflix, with dynamic movie and TV show content, user authentication, and a polished interface.

Originally, I planned to use static content, but after discovering the TMDB API, I integrated it to fetch live data such as trending movies, top-rated shows, and more. I also added embedded YouTube trailers to enhance the user experience.

Tech Stack
React (with custom hooks, Context API, and Portals)

Firebase (Authentication and Firestore)

TMDB API

Compound Components

Styled Components

Features
User authentication using Firebase

Live movie and TV data from TMDB API

Embedded trailers from YouTube

Clean, responsive UI built with Styled Components

Reusable custom React hooks and context

Setup Instructions
Clone the repository.

Install dependencies with npm install.

Replace the Firebase configuration in /lib/firebase.prod.js with your own Firebase project credentials.

Replace the TMDB API key in request.js with your own from TMDB.

Demo Screenshots
<img src="/images/demo1.png" alt="App Screenshot 1"> <img src="/images/demo2.png" alt="App Screenshot 2"> <img src="/images/demo3.png" alt="YouTube Trailer Screenshot">
Available Scripts
In the project directory, you can run:

npm start
Runs the app in development mode.
Open http://localhost:3000 to view it in the browser.

npm run build
Builds the app for production in the build folder.
Optimizes React for the best performance.

npm test
Launches the test runner in interactive watch mode.

npm run eject
This will copy all configuration files and dependencies into your project so you can modify them directly. This action is permanent.

Additional Resources
React Documentation

Create React App Documentation

Firebase Documentation

TMDB API Documentation

Styled Components Documentation

About Me
I’m Muhammad Haris, a frontend developer with a strong interest in React, Firebase, and building interactive web applications. This Netflix Clone was a project where I experimented with API integration, reusable components, and real-world user flows like authentication.