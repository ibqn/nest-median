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

## Create servises

```bash
pnpm nest generate module prisma
pnpm nest generate service prisma
```
