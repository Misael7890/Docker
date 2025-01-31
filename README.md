# Proyecto Docker Web
Este proyecto utiliza Docker para ejecutar un servidor web simple que muestra una página HTML.

## Investigación
¿Qué es un Docker?
Docker es una herramienta que te permite empaquetar una aplicación con todo lo que necesita para funcionar (código, bibliotecas, etc.) en un contenedor. Este contenedor luego se puede ejecutar en cualquier máquina que tenga Docker instalado, sin preocuparte por compatibilidades o configuraciones

¿Para qué sirve un Docker?
Docker se ha convertido en una herramienta esencial para desarrolladores y sysadmins, ya que simplifica el proceso de creación, prueba y despliegue de aplicaciones. Además, Docker permite aprovechar mejor los recursos del sistema, ya que varios contenedores pueden compartir el mismo kernel del sistema operativo

¿Como se usa un Docker?
Instalación de Docker: Instalar Docker en el sistema operativo de tu elección. 
Creación de una imagen: Definir un archivo llamado Dockerfile que especifica las instrucciones para construir la imagen del contenedor, incluyendo el sistema operativo base, las dependencias y el código de la aplicación. 
Construcción de la imagen: Utilizar el comando docker build para crear la imagen a partir del Dockerfile. 
Ejecución del contenedor: Iniciar un contenedor a partir de la imagen creada con el comando docker run. 
Gestión del contenedor: Utilizar comandos como docker ps para listar contenedores en ejecución, docker stop para detener un contenedor y docker rm para eliminarlo 


## Instrucciones para ejecutar
1. Construir la imagen con docker build -t mi-server ..
2. Ejecutar el contenedor con docker run -d -p 8080:80 mi-server.
3. Abrir en el navegador http://localhost:8080.
