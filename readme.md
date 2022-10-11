# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download Docker
2. Start Docker and verify it is running by using the following command in terminal:  
`docker -v`  
`docker-compose -v`
3. Run the following command from the root of this project to start the environment.  
`docker-compose up`
4. To verify that the environment has been successfully set up, browse the backend [here](http://localhost:3000/api/ping).
5. To verify that the environment has been successfully set up, browse the frontend [here](http://localhost:3001/register) and register a new user.
