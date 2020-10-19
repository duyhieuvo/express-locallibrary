# Express Simple Local Library

A small project following the tutorial from Mozilla: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs to get familiar with javascript and Node.js.

The entire environment is dockerized and can be run locally instead of on cloud services (heroku and mongodb atlas).

- Start the docker-compose environment:
> ./start-all.sh
- Stop the docker-compose environment:
> ./stop-all.sh

## Service endpoints

The mongodb and the library app can be accessed from the host machine with:

|      Service   |Endpoint                       |
|----------------|-------------------------------|
|MongoDB client  |http://localhost:3456          |
|Library app     |http://localhost:3000          |