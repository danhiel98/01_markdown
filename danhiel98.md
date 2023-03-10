# Hola 👋 Soy Daniel García
## Desarrollador web full stack [en proceso]

Soy un **apasionado de la programación** y las tecnologías de la información. Me encanta aprender y algún día me gustaría poder compartir mis conocimientos con otros.

Actualmente mi principal enfoque es el desarrollo web y estoy en proceso para convertirme en un *desarrollador web fullstack*.

El siguiente código crea un comando (mostused) que ejecuta el conjunto de instrucciones que se encuentra entre comillas simples, lo cuál devuelve la lista de los comandos que más he utilizado en la terminal:  
`alias mostused='history | awk '\'' {print $2}'\'' | sort | uniq -c | sort -nr | head -n 10'`  

El resultado de ejecutar el nuevo comando `mostused` fue el siguiente:

| Comando  | Descripción                       |
|----------|-----------------------------------|
| clear    | Limpia la pantalla                |
| cls      | Alias de cls                      |
| ls       | Lista el contenido de una carpeta |
| git      | CVS Git                           |
| cd       | Cambiar de directorio             |

Estos son mis alias más utilizados por el momento:
```bash
  mostused='history | awk '\'' {print $2}'\'' | sort | uniq -c | sort -nr | head -n 10'
  cls='clear
```
