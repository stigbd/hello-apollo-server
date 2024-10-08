# hello-apollo-server

A simple project to demonstrate how to create a GraphQL server using Apollo Server.

## Prerequisites
- Node.js
- npm

## Installation
1. Clone the repository
2. Run `npm install` to install the dependencies

## Usage
1. Run `npm start` to start the server
2. Open a browser and navigate to `http://localhost:4000` to access the GraphQL Playground
3. Enter the following query in the left pane and press the play button to execute the query
```graphql
query GetBooks {
  books {
    title
    author
  }
}
```
## Resources
https://www.apollographql.com/docs/apollo-server/getting-started
