Scheduler API
=================

Scheduling app that allows users to schedule an appointment with their provider and show the provider their schedule for the day.

## Technologies

This project was developedwith the following technologies:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Sequelize](http://docs.sequelizejs.com/)
- [Mongoose](https://mongoosejs.com/)
- [JWT](https://jwt.io/)
- [Bcrypt](https://www.npmjs.com/package/bcrypt)
- [Yup](https://www.npmjs.com/package/yup)
- [Docker](https://www.docker.com/docker-community)


## Installation

Clone the project:

```sh
git clone https://github.com/cicerogb/scheduler-api-node.js
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


