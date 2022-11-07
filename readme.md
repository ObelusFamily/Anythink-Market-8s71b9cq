# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
	clone the repo to ur local first. 
	1.first of all we install docker and runa container
	2.You can use <Docker -v> in your cmd or terminal to check whether the docker is installed
	3.Next we go into the ur project root and run <Docker-compose -v> -> this runs a cotainer docker app
	4.To check whether the project is up and running use a ping command in your browser by going to "http://localhost:3000/api/ping"

