# DevCamper API

## _API For Publishing and Managing Bootcamps and Courses_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

### Bootcamp Functionalities

- List all bootcamps
  - Pagination
  - Filtering (i.e. with NoSQL standard querying)
  - Selecting specific fields in result
  - Sorting by single/multi params
- List- Calculate the average rating from the reviews for a bootcamp on saving/updating review bootcamps within a radius specifying zip-code and covering distance
- Get a single bootcamp
- Create new bootcamp w/ proper auth
- Update a bootcamp w/ proper auth
- Upload a photo for bootcamp w/ proper auth
- Delete a bootcamp w/ proper auth

- Calculate the average rating from the reviews for a bootcamp on saving/updating review

### Course Functionalities

- List all courses in general

  - Pagination
  - Filtering (i.e. with NoSQL standard querying)
  - Selecting specific fields in result
  - Sorting by single/multi params

- List all courses for bootcamp
- Get a single course
- Create new course for a bootcamp w/ proper auth
- Update a course w/ proper auth
- Delete a course w/ proper auth
- Average cost calculation of all courses for a bootcamp on saving/updating course

### Review Functionalities

- List all reviews in general

  - Pagination
  - Filtering (i.e. with NoSQL standard querying)
  - Selecting specific fields in result
  - Sorting by single/multi params

- List all reviews for a bootcamp
- Get a single review
- Create a review w/ proper auth
- Update a review w/ proper auth
- Delete a review w/ proper auth
- Average rating calculation of all reviews for a bootcamp on saving/updating reviews

### User Functionalities

- List all users w/ proper auth
  - Pagination
  - Filtering (i.e. with NoSQL standard querying)
  - Selecting specific fields in result
  - Sorting by single/multi params
- Create a user w/ proper auth
- Update a user w/ proper auth
- Delete a user w/ proper auth

### Auth Functionalities

- User Registration (w/ "user" or "publisher" role)
- User Login
- User Logout
- Preview my profile
- Update my profile's name, email
- Update my password
- Forget/Reset password using token

## Misc Functionalities

- Proper authentication/authorization w/ JWT
- Owner cases implementation wherever applicable
- Password hashing
- Mongoose / other validations
- Proper error status code / message handling
- Taking only specific fields wherever saving/updating an entity, in order to prevent inputting system generated fields
- Database seeders
- Prevent NoSQL injections
- Add extra headers for security
- Prevent cross site scripting - XSS
- Add a rate limit for requests of 100 requests per 10 minutes
- Protect against http param polution
- Use cors to make API public (for now)
- API Documentation in Postman

### Documentation

> Postman API Documentation: [here](https://documenter.getpostman.com/view/14588654/VUxKU9jW)

## Tech

DevCamper API uses a number of open source projects to work properly:

- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework
- [MongoDB] - NoSQL Database

## Installation

Install the dependencies and start the server.

```sh
npm install
npm run dev
```

[//]: # "These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax"
[node.js]: http://nodejs.org
[express]: http://expressjs.com
[mongodb]: https://www.mongodb.com/
