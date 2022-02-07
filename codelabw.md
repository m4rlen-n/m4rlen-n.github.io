author: Nombre del autor
summary: Resumen del CodeLab
id: identificador-unico-del-codelab
categories: codelab,markdown
environments: Web
status: Published
feedback link: Un enlace en el que los usuarios puedan darte feedback (quizás creando un issue en un repositorio de git)
analytics account: ID de Google Analytics

# Prueba 

## Introducción
Duration: 0:02:00

¿Quieres crear un contenido similar a este tutorial? A continuación aprenderás **cómo crear tu propio CodeLab** en muy poco tiempo.

A la hora de crear un CodeLab tenemos dos opciones:
1. Usar un Documento de Google
2. Usar un fichero Markdown

En este CodeLab vamos a explicar la segunda opción y crear el nuestro usando un **fichero Markdown**. Esto nos garantiza la flexibilidad de reutilizar el archivo en otras ocasiones y la posibilidad de almacenarlo en nuestro repositorio de Git con cualquier otro código que pudiese ser útil en un tutorial. No obstante, puedes ver cómo hacerlo a partir de un Documento de Google en este [artículo de Juan Antonio Gómez](https://medium.com/shokmaster/google-codelab-en-5-minutos-5043f4cd21f4).

Este es otro ejemplo de cómo puede quedar un CodeLab generado:

**Créditos y Recursos:** 
* Este CodeLab **es una adaptación del original de Marc DiPasquale** que puedes encontrar aquí: [Enlace al CodeLab](https://www.marcd.dev/codelab-4-codelab)
* El archivo Markdown del original de Marc DiPasquale está accesible aquí: [codelab.md](https://github.com/Mrc0113/codelab-4-codelab/blob/master/codelab.md)
* [Google CodeLabs Tools Github](https://github.com/googlecodelabs/tools) - El repositorio que contiene la herramienta claat que vamos a utilizar
* [Google Group for CodeLab Authors](https://groups.google.com/forum/#!forum/codelab-authors) - foro de consulta sobre CodeLabs y discusión sobre futuras funcionalidades
* Si quieres acceder al archivo Markdown de este CodeLab, puedes hacerlo aquí: [codelab.md](https://github.com/DavidLMS/davidlms.github.io/blob/master/Practicas/crear-codelab/codelab.md)

## Preparación del entorno
Duration: 0:05:00

Para crear un CodeLab, necesitas tener instalados *Go* y *claat* (la herramienta por línea de comandos de codelabs).

A continuación puedes ver las instrucciones de instalación para los sistemas operativos más populares.

###Windows

Vamos a la [página de releases de claat](https://github.com/googlecodelabs/tools/releases) y **descargamos la versión apropiada**. Si tienes Windows de 64 bits, descargamos "claat-windows-amd64.exe".


###Linux (Probado en Ubuntu)

Vamos a la [página de releases de claat](https://github.com/googlecodelabs/tools/releases) y **descargamos la versión apropiada**. Si tienes Linux de 64 bits, descargamos "claat-linux-amd64".


**Abrimos una terminal** y accedemos a la carpeta en la que tengamos descargado el ejecutable de claat.

Le damos **permisos de ejecución**:

``` bash
sudo chmod +x claat-linux-amd64
```
(sustitumos claat-linux-amd64 por nuestra versión)



