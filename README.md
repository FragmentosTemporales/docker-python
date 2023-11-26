# Contenedor Docker Python


## 1. Instalación

Para descargar la aplicación del repo, se debe escribir el siguiente comando:

```
null
```


### Instalación de Docker Compose

Para instalar la aplicación debes ejecutar el siguiente código:

```
$ docker compose build
```


### Variables de entorno

Al interior de la carpeta /Sripts debes crear un documento env.env el cual debe contener las siguiente variables, puedes guiarte con el documento example.env :

```
FIRST_NAME=
LAST_NAME=
```


## 2. Ejecución

Para ejecutar la aplicación debes ingresar el siguiente comando:

```
$ docker compose run --rm scripts sh -c "python manage.py"
```


## 3.- ¿Qué estamos ejecutando?

Al ejecutar el manage.py estamos corriendo la función en app, la cual toma las variables de entorno en el archivo *env.env* y genera un saludo.


## 4.- Bibliografía

A continuación te dejo el link de la imagen de Python en Docker:

```
https://hub.docker.com/_/python/
```