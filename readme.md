# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repo
2. Make sure you have Docker installed on your machine
3. Run `docker-compose up`
4. To check everything is running correctly, open this page in your browser: http://localhost:3000/api/ping
5. Once this is running, create an account here: http://localhost:3001/register
