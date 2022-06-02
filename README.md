# Node.js Weight Tracker

![Demo](docs/build-weight-tracker-app-demo.gif)

This sample application demonstrates the following technologies.

* [hapi](https://hapi.dev) - a wonderful Node.js application framework
* [PostgreSQL](https://www.postgresql.org/) - a popular relational database
* [Postgres](https://github.com/porsager/postgres) - a new PostgreSQL client for Node.js
* [Vue.js](https://vuejs.org/) - a popular front-end library
* [Bulma](https://bulma.io/) - a great CSS framework based on Flexbox
* [EJS](https://ejs.co/) - a great template library for server-side HTML templates

**Requirements:**

* [Node.js](https://nodejs.org/) 14.x.x
* [PostgreSQL](https://www.postgresql.org/)
* [Free Okta developer account](https://developer.okta.com/) for account registration, login

## Install and Configuration

* Clone or download source files
*  2 ubuntu servers:
   1. Configure the database server (postgreSQL , set up using Docker)
   2. Configure the web server (npm install)
* Create a [free Okta developer account](https://developer.okta.com/) and add a web application for this app
* Copy `.env.sample` to `.env` and change the `OKTA_*` values to your application
* Initialize the PostgreSQL database by running `npm run initdb`
* Run `npm run dev` to start Node.js
* Application keep running even after restart (using PM2)

## example:

![tenor.gif](https://postimg.cc/GTTt4Phg)



The associated blog post goes into more detail on how to set up PostgreSQL with Docker and how to configure your Okta account.
