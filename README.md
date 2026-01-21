

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ npm install
```

## Environment variables

This project uses environment variables for configuration. Create a local
`.env` file based on `.env.example` and adjust values as needed.

```bash
$ cp .env.example .env
```

Keep `.env` out of version control and store only safe defaults in
`.env.example`. If you add new variables in code, remember to update
`.env.example` so others can run the project locally.

## Project structure (short)

- `src/` main application code.
- `src/main.ts` app bootstrap (creates Nest app and starts server).
- `src/app.module.ts` root module wiring controllers/providers.
- `src/app.controller.ts` + `src/app.service.ts` example controller/service.
- `src/users/` feature module with DTOs, entities, and module setup.
- `test/` e2e tests and Jest config.

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
