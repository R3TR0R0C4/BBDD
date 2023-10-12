## BDs

-Crear base de dades:

`CREATE DATABASE nom;`

-Eliminar base de dades:

`DROP DATABASE nom;`

-Mostrar bases de dades:

`SHOW databases;`

## Taules

-Crear taula:

`CREATE TABLE nom;`

-Mostrar taules (dintre d'una BBDD):

`SHOW tables;`

-Mostra contingut d'una taula:

`SELECT * FROM nom_taula;`

-Mostra contingut d’una taula amb limit:

`SELECT * FROM nom_taula LIMIT nº;`

## Users

-Crear usuari:

`CREATE USER 'username'@'host' IDENTIFIED BY 'password';`

-Mostra els usuaris:

`SELECT User, Host FROM mysql.user;`

-Eliminar usuari:

`DROP USER ‘user’@’host’;`

## Permisos

-Donar permisos a un usuari sobre una taula d'una BD:

`GRANT permís ON nomBD.nomTaula TO 'usuari'@host’;`

-Donar permisos a un usuari sobre unes columnes d’una taula d’una BD:

`GRANT permís (columna1, columna2) ON nomBD.nomTaula TO ‘usuari’@host’;`

-Treure permisos a un usuari sobre una taula d’una BD

`REVOKE permís ON nomBD.nomTaula FROM 'usuari'@host’;`
