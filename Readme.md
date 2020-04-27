# Ejercicio Docker y docker-compose

En este repositorio, vamos a crear nuestra aplicación contenerizada con Node.js y MongoDB.

El objetivo de este ejercicio es crear un contenedor para la aplicación de Node.js, un contenedor para la base de datos de MongoDb y un volumen con los datos almacenados en MongoDB. Poder conectarlo todo entre si y ejecutarlo.

Queremos quitar del contexto de docker, los datos del volumen.


Deberemos rellenar los siguientes archivos para poder ejecutarla:

- mongodb/Dockerfile
- node/Dockerfile
- docker-compose.yml
- .dockerignore