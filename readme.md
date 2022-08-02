# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Install docker](https://docs.docker.com/get-docker/) on the local machine. Verify if docker is installed and ready using the command `docker -v` or `docker-compose -v`.
2. Clone this repository(project) on the local machine.
3. Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
4. Backend Test: open the URL [http://localhost:3000/api/ping](http://localhost:3000/api/ping) on the browser.
5. Frontend Test: Open the URL [http://localhost:3001/register](http://localhost:3001/register) and create a new user.
