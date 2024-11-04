## Docker Assignment - Agile Software Practice.

__Name:__ ....QiYi Wang .....

__Demo:__ .... https://youtu.be/glZ_78fqfvY ....

### Database Seeding.

[Database auto-populate is implemented through the mongo-seed service defined in the docker-compose file. The service mounted a seeding.json file containing the data and used the mongoimport command to import the data into the MongoDB database, automating the database initialization process.]

### M.ulti-Stack.

[The development environment stack is configured through the docker-compose.override.yml file, adding mongo-seed for auto-populate the database and mongo-express for visually managing the database. The production stack is configured through the docker-compose.prod.yml file, omitting the development tools mongo-seed and mongo-express, and setting the api service to have full write permission.]
