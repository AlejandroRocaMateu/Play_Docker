# EJECUTANDO CONTENEDORES

##

* EJEMPLO 1:

En este ejemplo, lo primero que hemos hecho ha sido descargarnos primero un imagen iso de ubuntu, para despues ya descargado, podamos crear una contenedor y entrar a una shell de el, si no hemos descargado la iso, se nos descargara a la hora de poner el comando : docker run -it ubuntu:18.04 /bin/bash

![CONTENEDOR Y SHELL](https://github.com/AlejandroRocaMateu/Play_Docker/blob/0723091caf1740c3ebd27a14a93c6475780d1ae3/1.PNG)

##

* EJMPLO 2:

Este ejemplo, lo primero que hemos hecho ha sido, crear un contenedor de centOS y despues listar el contendido de su carpeta con el comando ls
(yo lo he hecho con Ubuntu porque me daba error si lo hacia con la iso de centOS)

![CONTENEDOR Y centOS](https://github.com/AlejandroRocaMateu/Play_Docker/blob/fd6d014eb1a4afdcb877c1dd578edc00c483989f/2.PNG)

##

* EJEMPLO 4:

En este ultimo ejemplo, lo que hemos hecho a sido crear lo primero un contenedor de debian 9 y mostrar su contenido de una carpeta.Con el comando docker run -it -w /etc debian:9 ls, lo primero hemos creado un contenedor de debian, cuando creas el contenedor se ejecuta tambien el ls desde el directorio etc.

![CONTENEDOR Y Debian](https://github.com/AlejandroRocaMateu/Play_Docker/blob/3d19726f8adcbf324aee87f5cc5975c8f7997c3e/4.PNG)


