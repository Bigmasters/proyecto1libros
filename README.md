# Project 1

Web Programming with Python and JavaScript


CREATE TABLE usuarios (id SERIAL PRIMARY KEY, usuario VARCHAR NOT NULL, contraseña VARCHAR NOT NULL);


CREATE TABLE opiniones (isbn VARCHAR NOT NULL,opinion VARCHAR NOT NULL, calificacion INTEGER NOT NULL,usuario VARCHAR NOT NULL);

CREATE TABLE libros (isbn VARCHAR PRIMARY KEY,title VARCHAR NOT NULL,author VARCHAR NOT NULL,year VARCHAR NOT NULL)
