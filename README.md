# Hackathon2022_Epic3

Este es el tercer y ultimo evento de la serie en el cual se busca generar una competencia (amigable) en la busqueda de "La Copa del Mundo" que se va a llevar a cabo en el ultimo dia del TechWeek2022 el día 17/11.

Para esto se les pedirá completar 2 postas, las cuales son individuales pero complementarias, por lo que se puede escribir todo en un mismo codigo con el nombre epic2_grupo_n.py (siendo 'n' el numero del grupo).

> Este codigo se pedirá ser escrito en el lenguaje Python, por lo que se debe tener un conocimiento previo del mismo.

Por lo que una vez terminadas las 2 etapas se debería tener 1 o 2 archivos .py con el codigo para validar las tareas + los archivos de texto que se pidan crear (si es que se piden).

Este é o segundo evento da série em que se busca gerar uma competição (amistosa) na busca por uma vaga para o 3º e último evento que acontecerá no último dia da TechWeek2022 no dia 17/11.

Para isso, será solicitado que eles completem 2 posts, que são individuais, mas complementares, para que tudo possa ser escrito no mesmo código com o nome epic2_group_n.py (onde 'n' é o número do grupo)

> Este código será solicitado a ser escrito na linguagem Python, portanto, você deve ter conhecimento prévio do mesmo.

Portanto, uma vez concluídas as 2 etapas, deve haver 1 arquivo .py com o código para validar as tarefas + os arquivos de texto que são solicitados a serem criados (se solicitados)...

## Infraestructura

<p align="center">
  <img src="Postas/infraTW.png" alt="Infraestructura Hackathon"/>
</p>

La infra consiste en un **Wireless Lan Controller 9800** (el cual será el caso de estudio) mas una **VM** con el nombre 'HT22' y **Python 3** ya instalado, la cual tiene resuelta la conexión **SSH** hacia el laboratorio que contienen al **WLC**.

> En este ultimo 'HT22' es en el cual nosotros debemos trabajar, escribiendo nuestros codigos y generando nuestros directorios de trabajo.

> Se le proporcionará a cada grupo la IP, User y Password de 'HT22', y la IP y User del **WLC** para que puedan trabajar.

A infra é composta por um **Wireless Lan Controller 9800** (que será o caso de estudo) mais uma VM com o nome 'HT22' e **Python 3** já instalado, que possui a conexão **SSH** com o laboratório que contém o **WLC** resolvido.

> Neste último 'HT22' é nele que devemos trabalhar, escrevendo nossos códigos e gerando nossos diretórios de trabalho.

> Cada grupo receberá o IP, Usuário e Senha do 'HT22', e o IP e Usuário do WLC para que possam trabalhar
>
> WLC9800:
> - IP = Se encuentra en la [planilla](Archivos/Credenciales.png)
> - USER = admin
> - PASS = hackathon
>
> HT22:
> - Conexión = ssh h2022-grpNN@10.54.118.3 (NN corresponde al numero del grupo)

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
Escribir un código en Python que en principio mantenga la conexión por SSH activada y luego otro que contenga un menú interactivo con distintas tareas.

Escreva um código em Python que mantenha uma interface de roteador ativa.

### Postas / fases
- 1.1 – [Habilitar SSH](Postas/P1.md)
- 1.2 – [Menú](Postas/P2.md)

## Validación de las etapas
Se le pedirá que guarde, desde el programa, el output del código en un directorio previamente creado (‘$HOME/output/’) con el nombre ‘posta_n.txt’ (siendo 'n' el numero de posta)

Validação das etapas

Será solicitado que você salve, do programa, a saída do código em um diretório previamente criado (‘$HOME/output/’) com o nome ‘post_n.txt’ (onde ‘n’ é o número do post)
