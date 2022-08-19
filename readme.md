# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1. Install the appropriate version of Docker from this link: https://docs.docker.com/get-docker/. Follow the instructions in the website
2. Verify Docker is installed by running "docker -v" and "docker-compose -v"
3. In terminal, navigate to the project root directory
4. Run "docker-compose up" to load Anythink's backend and frontend
5. Wait... Wait what seems like a long time.
6. In your browser, navigate to http://localhost:3001/register to verify everything is working properly

