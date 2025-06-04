# Golang and-React.js Movie Platform

## Used Tools:

- [Golang](https://github.com/golang/go)
- [React.js](https://github.com/facebook/react)
- [Docker Compose](https://github.com/docker/compose)
- [Chi Router](https://github.com/go-chi/chi)
- [JWT authentication and authorization](https://github.com/golang-jwt/jwt)
- [PGX PostgreSQL driver](https://github.com/jackc/pgx)
- [Go supplementary cryptography](https://github.com/golang/crypto)
- [GraphQL](https://github.com/graphql-go/graphql)

## How to run?

### 1- Install Back-end Dependencies

cd to the go-movies-back-end directory and run this command:

```bash
go mod download
```

### 2- Install Front-end Dependencies

cd to the go-movies-front-end directory and run this command:

```bash
npm install
```

### 3- Run Database

cd to the root level of project and run this command:

```bash
docker-compose up -d
```

### 4- Run Back-end API

cd to the go-movies-back-end directory and run this command:

```bash
go run ./cmd/api
```

### 5- Run React.js

cd to the go-movies-front-end directory and run this command:

```bash
npm start
```