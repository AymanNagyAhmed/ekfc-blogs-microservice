## Repositories
- [Full project install using docker (Recommended)](https://github.com/AymanNagyAhmed/ekfc-t)
-[Users Microservice](https://github.com/AymanNagyAhmed/ekfc-users-microservice)


# Blogs microservice

## Prerequisites
- Node.js (v22.11.0)
- MongoDB
- RabbitMQ


## Database Configurations
- DB_HOST=127.0.0.1
- DB_TYPE=mongodb
- DB_NAME=blogs_ms_db
- DB_USER=admin
- DB_PASSWORD=Admin1357Admin
- DB_PORT=27017

## RabbitMQ Configurations

- RMQ_UI_PORT=15672
- RMQ_HOST=127.0.0.1

- RMQ_PORT=5672
- RMQ_USER=guest
- RMQ_PASSWORD=guest
- RMQ_EXCHANGE=blogs_exchange
- RMQ_BLOGS_QUEUE=blogs_queue

## JWT Configurations
- JWT_SECRET=
- JWT_EXPIRES_IN=1d

## Regular Installation [or Install using docker](https://github.com/AymanNagyAhmed/ekfc-task)

### Local Development Setup
1. Clone the repository
2. copy .env.dev to .env
3. Change env variables
4. yarn install
5. yarn start:dev
6. visit swagger docs "http://localhost:4004/api/docs"

