# Music-Library

This is a music library API which can perform CRUD operations on a database. 

Please note, there is no GUI for this API therefore an application like [Postman](https://www.postman.com/) is recommended to interact with the API.

## Technologies and Concepts Covered

Created using [Node.js](https://nodejs.org/en/), [Express.js](https://expressjs.com/). The database is PostgreSQL](https://www.postgresql.org/) with [pgAdmin](https://www.postgresql.org/ftp/pgadmin/pgadmin4/) & uses a [Docker](https://www.docker.com/) container. 

Testing has been done using [Mocha](https://mochajs.org/) & [Chai](https://www.chaijs.com/).

## Getting Started

After Forking and Cloning the repo: https://github.com/CB715/music-library add the relevant dependencies with; ```
npm i
```

The API endpoints are:

| HTTP Method | URL | Description |
| ------------- | ------------- | ------------- |
| POST | / | Creates an artist |
| GET | / | Get all artists |
| GET | /{id} | Get artist by ID |
| PUT | /{id} | Update an artist record |
| PATCH | /{id} | Update an artist record |
| DELETE | /{id} | Delete an artist by ID |


### To do

* Add an additional relational database to link artists to albums.