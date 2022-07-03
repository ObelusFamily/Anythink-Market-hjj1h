# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

On our first setup , we will need to first install docker:
https://docs.docker.com/get-docker/

Then we can verify docker is installed:
Put this come on your terminal :
docker -v
Then we will compose new docker by this command:
docker-compose -v

We are ready to fly with our new docker, run:
docker-compose up

If it all went well - we will be able to get response from :
http://localhost:3000/api/ping
