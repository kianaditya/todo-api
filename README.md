# TODO API

This is an api to maintain a todo list.

## Built with
* [Postgres](https://www.postgresql.org/) for database
* [Express](https://expressjs.com/) for web framework based on Node.js 

## HOW To Access API

clone repo to local directory and `npm install` to install dependencies.

`npm run start:dev` to run server

#### TODO
* to get list of TODO - `/api/todos` get request
* to create a new TODO - `/api/todos` post request
* to get specific TODO with id - `/api/todos/:id` get request
* to update specific TODO with id -`/api/todos/:id` put request
* to delete specific TODO with id - `/api/todos/:id` delete request
#### Todo Items per TODO
* to create a new TODO item - `/api/todos/:todoId/items` post request
* to update specific TODO item - `/api/todos/:todoId/items/:todoItemId` put request
* to delete specific TODO item - `/api/todos/:todoId/items/:todoItemId` delete request

