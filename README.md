# Docker-Compose-Examples

## Postgres
 - docker-compose -f docker-compose.yaml -f docker-compose.dev.yaml --env-file .env.pass.dev -p postgres-dev up -d

## PgAdmin
### NOTE: In the command, it will associate postgres network. So is needed run last command
 - docker-compose --env-file .env.pgadmin -p exp-pgadmin up -d

## Selenium webdriver
 - docker-compose up -d

## RabbitMQ
 - docker-compose -f docker-compose.yaml --env-file .env.rabmq up -d

##  Elasticsearch
 - docker-compose up -d

 ##  Jenkins
 - docker-compose up -d

