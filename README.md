# Docker-01-EjecutandoContenedores
## EJEMPLO 1: 
### Primero vamos a descargar  una imagen de manera previa
#### con el siguiente comando la descargaríamos $docker pull ubuntu:18.04

![h1](https://user-images.githubusercontent.com/103216638/166204634-3c703873-7dd3-4784-a94e-1e0f525ce07d.PNG)

### Ahora crearemos un contenedor de ubuntu:18.04
#### Ejecutaríamos el siguiente enlace docker run -it ubuntu:18.4 /bin/bash

![h2](https://user-images.githubusercontent.com/103216638/166205034-09a72264-6ec3-4f4d-be5b-f953747eb3f6.PNG)

## EJEMPLO 2:
### Crear un contenedor y listar el contendido de la carpeta
#### Ejecutaríamos el mismo comando de antes (el docker run) y meteríamos un ls

![h3](https://user-images.githubusercontent.com/103216638/166205840-c7dd6980-9045-4475-a570-b9ca9e47a637.PNG)

## EJEMPLO 4:
### Crear un contenedor y mostrar el contenido de una carpeta
#### Crearíamos un contenedor de  debian 9 y mostraríamos el contenido con el siguiente comando:  docker run -it -w /etc debian:9 ls

![h4](https://user-images.githubusercontent.com/103216638/166206310-5c03b897-5c1f-412d-a4a7-b19fe4cf7e53.PNG)

#### 1 - Mostramos los contenedores en ejecución 

![h6](https://user-images.githubusercontent.com/103216638/166206730-a1756883-7adf-4ea0-a37f-7d902047f155.PNG)

#### 2 - Mostrar todos los contenedores creados ya estén en ejecución

![h7](https://user-images.githubusercontent.com/103216638/166206795-1a54b891-619e-4251-8d48-006fcaccfd98.PNG)

