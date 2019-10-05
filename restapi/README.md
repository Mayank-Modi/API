The Endpoint for API are,

## Login
* `http://localhost:8000/api/auth/login`
* (POST)This endpoint takes username and password, and on correct credentials, it return a Token to be used in Header for further actions.

## Logout
* `http://localhost:8000/api/auth/logout`
* (GET)This endpoint takes only Authentication Token in header to succesfully logout the user.

## Register
* `http://localhost:8000/api/auth/register`
* (POST)This endpoint is used to create new user, it takes following input
- username
- email
- password


### Note: Default credentials for SUPER USER is admin:admin