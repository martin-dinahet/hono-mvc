# Honoko

A super simple, lightweight backend server using Hono.


## Features

- Secure authentication support with `better-auth`
- Full Typescript support
- Custom, production-ready auth guards for your routes
- Request validation with `zod`
- Custom error handling
- Postgres database setup with Docker
- ORM with Prisma

## Quickstart

```
git clone https://martin-dinahet/honoko.git <your-project>
cd <your-project>
npm run db:up
npm install
npm run db:migrate
npm run db:generate
npm run dev
```
