# Docker Assignment

## Set-up Commands

Start up the containers: docker-compose up -d

Login to postgres: docker exec -it postgres psql -U user

This command will be determined by the docker-compose.yml file if different env variables are used.

Eg. docker exec -it postgres psql -U user testdb as this takes a database name.

Show tables: \dt

Show databases: \l

CREATE TABLE STUDENT (ID INT PRIMARY KEY NOT NULL, NAME text);
INSERT INTO  STUDENT (id,name) values (1,'Komal Parakh');
INSERT INTO  STUDENT (id,name) values (1,'Mohammed Shoab');

SELECT * from STUDENT;

## Access the server 
Go to http://localhost:10080/ to view phppgadmin
