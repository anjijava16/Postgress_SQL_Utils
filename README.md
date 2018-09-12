# Postgress_SQL_Utils

Username:postgress
Password:root
IP: 5432
Host: localhost



===============================================================

$ \help

$ psql -h localhost -p 5432 -U postgress testdb
$ CREATE DATABASE dbname;
# List Of Database 
$ \l
#Connect Database
\c testdb;
# Direct Connect Database 
psql -h localhost -p 5432 -U postgress testdb

DROP DATABASE [ IF EXISTS ] name
dropdb -h localhost -p 5432 -U postgress testdb

$ \d  (list of databases)

$ \d company

DROP TABLE table_name;

DatabaseNme:mydb
