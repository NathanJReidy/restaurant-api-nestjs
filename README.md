## Description

This is a NestJS API that implements CRUD functionality with authentication and authorisation for users via Auth0. This is an implementation of this tutorial: https://auth0.com/blog/developing-a-secure-api-with-nestjs-getting-started/

## Installation

```bash
$ npm install
```

## Running the app

The following environment variables must be specified in a .env file before running the app:

- PORT=3000
- AUTH0_ISSUER_URL=https://dev-cscnbaq1.us.auth0.com/
- AUTH0_AUDIENCE=https://menu-api.demo.com

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

After running the server, a sample client can be accessed at https://dashboard-v1.whatabyte.app/home
