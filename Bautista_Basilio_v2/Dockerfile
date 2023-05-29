#Version 2 del Dockerfile

FROM nginx:latest

LABEL description="Contenedor Nginx personalizado con volumen persistente"

#Copiar archivos ed configuracion de Nginx

Copy nginx.conf /etc/nginx/nginx.conf

#Crear volumen persistente para el archivo index.html

VOLUME /usr/share/nginx/html

#Copiar el archivo index.html incial

COPY index.html /usr/share/nginx/html

#Exponer el puerto 8080

EXPOSE 8080