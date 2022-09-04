# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_


## Setting up local environment

1. Clone the repository.

2. Make sure [Docker](https://docs.docker.com/get-docker/) is installed.
    > You can verify the installation by running `docker -v` and `docker-compose -v` commands 

3. Now from the project root directory run below command to build 
   and run the containers of frontend, backend and database
   
        `docker-compose up`
	
    > To confirm, head to the `http://localhost:3000/api/ping` url in your browser, and if you get a json message in your browser, you're good to go.