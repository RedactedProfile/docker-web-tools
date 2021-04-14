# Docker Tools for Web

---

ps. I'm open to suggestions for a better name.  

---

This repository contains pre-configured docker-compose managed singular instances of popular tools, geared towards
web application developers.

## Included

### MySQL 5.7
tools: 
 - phpMyAdmin

`docker-compose up -d mysql_legacy`

### MySQL 8
tools: 
 - phpMyAdmin

`docker-compose up -d mysql`
 
### MariaDB 11.5
tools: 
 - phpMyAdmin

`docker-compose up -d mariadb`

### PostgreSQL 11.5
tools: 
 - pgAdmin
 
`docker-compose up -d postgres`
`docker-compose up -d pgadmin`

### MongoDB Community 4.2
tools:
 - Mongo Express Admin
 
`docker-compose up -d mongodb`

### ElasticSearch 7.3.2

`docker-compose up -d elasticsearch`

### Redis 5

`docker-compose up -d redis`

### RabbitMQ 3.7

`docker-compose up -d rabbitmq`

### Neo4j 3.5

`docker-compose up -d neo4j`
