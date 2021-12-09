## Description

A NestJS API that implements CRUD functionality with authentication and authorisation for users via Auth0. This is an implementation of this tutorial: https://auth0.com/blog/developing-a-secure-api-with-nestjs-getting-started/

## Installation

```bash
$ npm install
```

## Running the app

The following environment variables must be specified in .env before running the app:

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

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
