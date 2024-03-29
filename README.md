# Flask GraphQL React

## Server with Flask

Flask is a lightweight Python server which can easily supply a GraphQL API.

## GraphQL with Ariadne

Ariadne allows the creation of a GraphQL of API from a schema. It's easy to use and connects well with Flask.

## Frontend with React

Demonstrates queries and mutations for our API with a simple React frontend.

## How to run

Clone the repo then:

### Server

Navigate to the server folder `cd server`, install dependencies (use a virtual environment if you wish) run `python server.py` to start the backend. You should be able to access the GraphQL playground at [localhost:5000](localhost:5000)

### Client

Navigate to the client folder `cd client`, install dependencies with `yarn` and run run the frontend server, `yarn start`. You should be able to access the frontend at [localhost:3000](localhost:3000). You can now start communicating with the backed via the React UI.
