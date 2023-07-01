# Docker-Compose-Examples

## Postgres
 - docker-compose -f docker-compose.yaml -f docker-compose.dev.yaml --env-file .env.pass.dev -p postgres-dev up -d

## Selenium webdriver
 - docker-compose up -d

## RabbitMQ
 - docker-compose -f docker-compose.yaml --env-file .env.rabmq up -d

##  Elasticsearch
 - docker-compose up -d