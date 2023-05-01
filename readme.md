## Description

project was created by

```bash
npx @nestjs/cli new nest-median
```

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Migrate the database

```shell
pnpm prisma migrate dev --name "init"
```

seed database with initial data

```bash
pnpm prisma db seed
```

## Create services

```bash
pnpm nest generate module prisma
pnpm nest generate service prisma
```

## Create resource

create articles

```bash
pnpm nest generate resource
# ? What name would you like to use for this resource (plural, e.g., "users")? articles
# ? What transport layer do you use? REST API
# ? Would you like to generate CRUD entry points? Yes
```

create users

```shell
pnpm nest generate resource
# ? What name would you like to use for this resource (plural, e.g., "users")? users
# ? What transport layer do you use? REST API
# ? Would you like to generate CRUD entry points? Yes
```

create auth

```shell
pnpm nest generate resource
# ? What name would you like to use for this resource (plural, e.g., "users")? auth
# ? What transport layer do you use? REST API
# ? Would you like to generate CRUD entry points? No
```

## Using prisma studio

```shell
pnpm prisma studio
```

## Generate prisma client

```shell
pnpm prisma generate
```
