## Note

This is a modified version of the GraphQL Server running at [SWAPI GraphQL](http://graphql.org/swapi-graphql/) and a clone of this [REPO](https://github.com/graphql/swapi-graphql). It hs been modified to return JSON instead of a graphiql interface, and to allow Cross-Origin Resource Sharing. 

SWAPI GraphQL Wrapper
=====================

A wrapper around [SWAPI](http://swapi.co) built using GraphQL.

Uses:

* [graphql-js](https://github.com/graphql/graphql-js) - a JavaScript GraphQL runtime.
* [DataLoader](https://github.com/facebook/dataloader) - for coalescing and caching fetches.
* [express-graphql](https://github.com/graphql/express-graphql) - to provide HTTP access to GraphQL.
* [GraphiQL](https://github.com/graphql/graphiql) - for easy exploration of this GraphQL server.

Try it out at: http://graphql.org/swapi-graphql

## Getting Started

Install dependencies with

```sh
npm install
```

or
```sh
yarn
```

## Local Server

A local express server is in `./server`. It can be run with:

```sh
npm start  //start script currently utilizes yarn, change if using npm
```
or
```sh
yarn start //babel-node must be installed globally for start script to run
```

A GraphiQL instance will be opened at http://localhost:8080/ (or similar; the actual port number will be printed to the console) to explore the API.
