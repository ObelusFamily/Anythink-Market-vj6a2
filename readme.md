# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To get up and going,
* [Install Docker](https://docs.docker.com/get-docker/)
* `Clone` the [Repo](https://github.com/ObelusFamily/Anythink-Market-vj6a2)
* Ensure you have Docker running by running `docker -v` and `docker-compose -v` in your terminal.
* Navigate to the project `Base` directory, run `docker-compose up` in your terminal
* Wait for the scripts to finish runnng
* Navigate to `http://localhost:3000/api/ping` to verify the backend is up and functional
