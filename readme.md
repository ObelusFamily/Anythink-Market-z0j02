# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
- Install docker from http://docker.io
- Check docker installation by running: `docker -v` and `docker-compose -v`
- run `docker-compose up` and verify the frontend and backend is running by visiting: `http://localhost:3000/api/ping` and `http://localhost:3001/register`

