# Live Chat App
A simple live GraphQL chat app built using React, Node, Apollo Server/Client and TypeGraphQL.

### Server
- Run `yarn` to install deps
- Make `.env` file with `PORT=9000`
- Run `yarn watch` to compile TS files
- In another terminal, run `yarn dev`
- Visit `localhost:9000/graphql` to view GraphQL Playground

### Client
- Run `yarn` to install deps
- Run `yarn start`
- Visit `localhost:3000`

## GraphQL API Endpoints
- `/graphql`: has `createChat` mutation and `allChats` query resolvers
- `/subscriptions`: has `messageSent` subscription

### UI
- material-ui -- not yet :)