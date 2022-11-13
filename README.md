# MOVIE-REVIEW -> PLEASE CLICK LINKS FOR FRONTEND & BACKEND SERVICES

LINKS:

FRONTEND: https://github.com/nanotechkarl/streaming-app

BACKEND: https://github.com/nanotechkarl/streaming-service

# Description

A collection of movies with reviews from people.

![moviereview](./mr.png)

# Technologies used:

- React - Typescript
- HTML - SCSS
- Redux Toolkit
- Loopback 4
- MongoDB
- Sonarqube
- React Testing Library + Jest

# Features

- View movies together with their actors and reviews(Public)
- Give reviews and ratings to movies(User only)
- Add movies and actors using the dashboard page(Admin only)

# Models

![ERD](./erd.png)

This app has the following models:

- User - a model representing the users of the app.
- Movie - a model representing the movies of the app.
- Actor - a model representing the connection between the movies and the actors.
- Actor Details - a model representing the details of an actor
- Review - a model representing the reviews of a user to a movie.

# Controllers

- user - controller for login/register user, fetch user info, update user info, delete users
- movies - controller for create, fetch,search, update, delete movies
- actor details - controller for create, fetch, search, update, delete actors
- reviews - controller for create, fetch, update, delete reviews
- actor - controller for create, fetch, delete connection between movies and actors

# Tests

- Use `npm test` to run test on both FE and BE services.
- Use `npx jest --coverage` to see coverage on both services.

Sonarqube Scanner Results
Front-End:
![FE](./sfe.png)

Back-End:
![BE](./sbe.png)
![BEC](./sbe1.png)
