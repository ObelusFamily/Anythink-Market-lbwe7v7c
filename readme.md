# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repository.
2. After cloning make sure that docker and docker-compose is installed by running these command `docker -v` and `docker-compose -v`. If its not installed visit https://docs.docker.com/get-docker/ to get the installation done according to your system.
3. Go inside the cloned directory and run `docker-compose up`, make sure you're inside the right directory before running the command and also make sure that `docker-compose.yml` file exists in that directory.
4. Wait for the setup to finish, it might take some time depending on your internet speed.
5. After the setup and installation is done, go to https://localhost:3000 or https://localhost:3001.

