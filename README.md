# secure-cv

[![Build Status](https://travis-ci.com/michal-wrzosek/secure-cv.svg?branch=master)](https://travis-ci.com/michal-wrzosek/secure-cv)

---

This project was bootstrapped with `web-admin-api` boilerplate:
https://github.com/michal-wrzosek/web-admin-api

# web-admin-api

Fullstack boilerplate of 3 services:

- **web** - server side rendered React app facing regular users
- **admin** - single page React app for admins
- **api** - GraphQL Apollo API

`+`

- **mongodb** - as a database

_This project is currently in progress._

# Development

This repository is in fact a monorepo (lerna)

**To install all dependencies run:**

```
npm run bootstrap
```

**To start development server:**

```
# make sure you have Docker installed
docker-compose up --build
```

# API Service

### Tech stack:

- Typescript
- Express.js
- GraphQL
- Apollo Server
- Mongoose
- MongoDB
- JWT access tokens

### Testing stack:

- Mocha + Chai
- Supertest
- mongodb-memory-server

# WEB Service

_Work in progress_

### Tech stack:

- Typescript
- Next.js
- React
- Hooks + Context API
- Apollo Boost
- Styled Components
- Styled System

### Testing stack:

- _WIP_

# ADMIN Service

_Work in progress_

# Deployment
