# Hackathon2022_Epic1

Este es el primero de una serie de 3 eventos, en los cuales se busca generar una competencia (amigable) en la busqueda de una plaza para el 3er evento y final que se va a llevar a cabo en el ultimo dia del TechWeek2022 el día X.

Para esto se les pedirá completar 3 postas, las cuales son individuales pero complementarias, por lo que se puede escribir todo en un mismo codigo con el nombre epic1_grupo_n.py (siendo 'n' el numero del grupo).

> Este codigo se pedirá ser escrito en el lenguaje Python, por lo que se debe tener un conocimiento previo del mismo.

Por lo que una vez terminadas las 3 etapas se debería tener 1 archivo .py con el codigo para validar las tareas + los archivos de texto que se pidan crear (si es que se piden).

## Infraestructura 

<p align="center">
  <img src="Postas/infraTW.png" alt="Infraestructura Hackathon"/>
</p>

La infra consiste en un **Wireless Lan Controller 9800** (el cual será el caso de estudio) mas una **VM** con el nombre 'HT22' y **Python 3** ya instalado, la cual tiene resuelta la conexión **SSH** hacia el laboratorio que contienen al **WLC**.

> En este ultimo 'HT22' es en el cual nosotros debemos trabajar, escribiendo nuestros codigos y generando nuestros directorios de trabajo.

> Se le proporcionará a cada grupo la IP, User y Password de 'HT22', y la IP y User del **WLC** para que puedan trabajar.
>
> WLC9800:
> - IP = 10.54.109.10X (ip del wlc)
> - USER = admin
> - PASS = hackathon
>
> HT22:
> - Conexión = ssh h2022-grpNN@10.54.118.3 (ip de la vm)

## Comandos Linux utiles
No es obligatorio el conocimiento profundo de manejo de CLI Linux ya que ejecutaremos tareas basicas.

- Listar archivos
~~~bash
>>> ls
~~~
- Listar archivos (ocultos tambien)
~~~bash
>>> ls -a
~~~
- Moverse entre directorios
~~~bash
>>> cd <nombre_carpeta>
~~~
- Moverse al directorio root
~~~bash
>>> cd ~
~~~
- Crear directorio
~~~bash
>>> mkdir <nombre_carpeta>
~~~
- Crear archivo
~~~bash
>>> nano <nombre_archivo>
~~~
~~~bash
>>> vim <nombre_archivo>
~~~
- Ver contenido archivo
~~~bash
>>> cat <nombre_archivo>
~~~
- Ejecutar script python3
~~~bash
>>> python3 <nombre_archivo>.py
~~~
- Descargar libreria python3
~~~bash
>>> pip3 <nombre_libreria>
~~~

## Objetivo final
Escribir un código en Python para crear un usuario dentro del WLC.

### Postas
- 1.1 – [Obtener JSON](Postas/P1.md)
- 1.2 – [Conexión SSH](Postas/P2.md)
- 1.3 – [Creación de usuario](Postas/P3.md)

## Validación de las etapas
Se le pedirá que guarde, desde el programa, el output del código en un directorio previamente creado (‘$HOME/output/’) con el nombre ‘posta_n.txt’ (siendo 'n' el numero de posta)
