# Median

## Description

A back-end REST API for a blog application called Median, a Medium clone using NestJS, Prisma ORM, PostgreSQL for database in a docker container and Swagger for documentation

## Prerequisites

This project requires [Node.js](https://nodejs.org/) and [Docker](https://www.docker.com/) to be installed. Node version ```16.15.1``` is used here.

```bash
# check if node is installed
node --version
```

## Installation

Clone the repository and install dependencies

```bash
# clone the repository
$ git clone https://github.com/educhinski/median.git

# cd into the folder
$ cd median

# install the dependencies
$ npm install
```

## Running the app

Make sure the database is running before serving the files

```bash
# run the database
$ docker compose up -d

# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

The rest api is available at <http://localhost:3000/articles>

The documentation endpoint is available at <http://localhost:3000/api>

## Stay in touch

- Author - [Edwin Mambo](https://github.com/educhinski)
- Twitter - [@edwin_mambo](https://twitter.com/edwin_mambo)

## License

Nest is [MIT licensed](LICENSE).
