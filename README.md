Scheduler API
=================

Scheduling app that allows users to schedule an appointment with their provider and show the provider their schedule for the day.

## Technologies

This project was developedwith the following technologies:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [nodemon](https://nodemon.io/)
- [Sucrase](https://github.com/alangpierce/sucrase)
- [Sequelize](http://docs.sequelizejs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [node-postgres](https://www.npmjs.com/package/pg)
- [JWT](https://jwt.io/)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)
- [Yup](https://www.npmjs.com/package/yup)
- [Docker](https://www.docker.com/docker-community)


## Installation

Clone the project:

```sh
git clone https://github.com/CiceroGB/scheduler-api-node.js
```

Install the dependencies:

```sh
yarn
```

Create database and fill fields in .env file.

To create tables:

```sh
yarn sequelize db:migrate
```

To start the server:

```sh
yarn start
```

If you are in development environment:

```sh
yarn dev
```
##
###### Inspired by the project developed by Rocketseat


