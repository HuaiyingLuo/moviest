# Moviest - Movie Review App

This project is a Movie Review Application where users can:

* Browse a collection of movies.
* View movie trailers.
* Add and view movie reviews.

The application follows a loosely coupled architecture:

* Backend: Java with Spring Boot and MongoDB.
* Frontend: React.


## Backend

* RESTful API for movies and reviews.
* MongoDB as a NoSQL database for data storage.
* Environment variable configurations.

Run the backend using the following command:
```
mvn spring-boot:run
```

runs on http://localhost:8080 by default

## Frontend

* React components for Home, Header, Trailer, and Reviews.
* Bootstrap for styling and responsive design.
* React hooks for state management and data fetching.

Run the frontend using the following command:
```
npm start
```

runs on http://localhost:3000 by default

