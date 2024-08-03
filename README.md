# Product Microservice

This is the microservice to manager products.

#### Protocol used: `TPC`

## Installation

```bash
$ npm install
```

## Add .env file

Create an `.env` file based on the `env.template`.

## Running migration DB

```bash
$ npx prisma migrate dev
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
