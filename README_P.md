# Hackathon2022_Epic3

[Leer en Español](README.md)

Este é o terceiro e último evento da série em que busca gerar uma competição (amistosa) em busca da “Copa do Mundo” que acontecerá no último dia da TechWeek2022 no dia 17/11.

Para isso, serão solicitados a completar 2 postagens, que são individuais mas complementares, para que tudo possa ser escrito no mesmo código com o nome epic2_grupo_n.py (onde 'n' é o número do grupo).

> Este código será solicitado a ser escrito na linguagem Python, portanto você deve ter conhecimento prévio dela.

Portanto, uma vez concluídas as 2 etapas, você deve ter 1 ou 2 arquivos .py com o código para validar as tarefas + os arquivos de texto que são solicitados a serem criados (se solicitados).

## A infraestrutura

<p align="center">
  <img src="Postas/infraTW.png" alt="Infraestructura Hackathon"/>
</p>

A infra é composta por um **Wireless Lan Controller 9800** (que será o caso de estudo) mais uma VM com o nome 'HT22' e **Python 3** já instalado, que possui a conexão **SSH** com o laboratório que contém o **WLC** resolvido.

> Neste último 'HT22' é nele que devemos trabalhar, escrevendo nossos códigos e gerando nossos diretórios de trabalho.

> Cada grupo receberá o IP, Usuário e Senha do 'HT22', e o IP e Usuário do WLC para que possam trabalhar

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

Escreva um código em Python que inicialmente mantenha a conexão SSH habilitada e depois outro que contenha um menu interativo com diferentes tarefas.

### Postas / fases
- 1.1 – [Ativar SSH](Postas/P1_P.md)
- 1.2 – [Menú](Postas/P2_P.md)

## Validação das etapas

Será solicitado que você salve, do programa, a saída do código em um diretório previamente criado (‘$HOME/output/’) com o nome ‘post_n.txt’ (onde ‘n’ é o número do post)



