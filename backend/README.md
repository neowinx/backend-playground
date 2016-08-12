Backend Playground
==================

This repo serves as playground for the diferent technologies available for backend microservices. Every project has to offer tests for at least the next operations:

- Services for every CRUD operation with all the posible alternatives
- Services for serving other services with some transformation of the response if posible
- Services for file serving directly and indirectly

Pattern
-------

The pattern of the project naming is as follows:

[MICROSERVICE]-[MAPPER]-[DATA]

Where MICROSERVICE is the framework/technology, MAPPER refers of the mapper framework or technology used to transform requests and responses to intermediate data for data persistence, and DATA the underlying data layer used, whereas this is a file, a database, a cloud service, etc.

play-ebean-postgres
play-ebean-mongo
play-hibernate-postgres
play-hibernate-mongo
jersey-ebean-postgres
jersey-ebean-mongo
jersey-hibernate-postgres
jersey-hibernate-mongo