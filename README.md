# Servidor tomcat + proxy apache con docker-compose

Crea un contenedor docker con un server apache2 con dos volumenes mapeados al directorio del proyecto:
1. Un volumen para los archivos que sirve mapeado en `./html`.
2. Un volumen para los archivos de configuración en `./conf`

Ver: [httpd docker image](https://hub.docker.com/_/httpd) para mas detalles de configuración.