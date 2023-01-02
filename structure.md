# Structure for bookstore API

## Routes

- GET / ==> Home route

- POST /register ==> Register a new user
- POST /login ==> Authenticate a new user
- POST /logout ==> Logout a new user

### Book Routes

- GET /api/v1/books ==> Return all books (Secured)
- GET /api/v1/books/:id ==> Returns a particular book (Secured)
- POST /api/v1/books ==> Adds new book (Secured)
- PUT /api/v1/books/:id ==> Update a book by id (Secured)
- DELETE /api/v1/books/:id ==> Delete a book by id (Secured)

### Author Routes

- GET /api/v1/authors ==> Return all authors (Secured)
- GET /api/v1/authors/:id ==> Returns a particular author (Secured)
- POST /api/v1/authors ==> Adds new author (Secured)
- PUT /api/v1/authors/:id ==> Update an author by id (Secured)
- DELETE /api/v1/authors/:id ==> Deletes an author by id (Secured)

## Other functionalities

- Rate Limiting
- Security middleware
- Good logging
- Validation
