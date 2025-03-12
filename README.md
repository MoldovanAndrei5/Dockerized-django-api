# Django API for user management

The API is dockerized and it contaions a docker-compose.yml file which makes it easier to run

## Testing
It can be tested by running the following command: docker compose up --build
You can test the api at localhost:8000/api/ or in the terminal

## Requests
To do a GET request: localhost:8000/api/users/
To create a user:  localhost:8000/api/create/
To do an operation on one user (get user by id, UPDATE, DELETE, type the id of the user: localhost:8000/api/users/1 (user with id 1)
