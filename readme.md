# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps to setting up a local environment :-

1. Install Docker :- https://docs.docker.com/get-docker/
2. Run command from the project root directory in a terminal :- docker-compose up
3. Check if Backend is running at :- http://localhost:3000/api/ping
4. Check if Frontend is running at :- http://localhost:3001/register

If everything is working properly then it's done!