# docker-rvm_ypb
# Hecho por Yohancel Pita y Rowan Vowler

# Objetivo

El objetivo de este Dockerfile es crear una imagen basada en Ubuntu 24.04 que contenga un entorno de visualización (VNC) por el cual se pueda utilizar VScode el cual se inicia automaticamente.

# Pasos a seguir

Descargar los archivos del repositorio y ponerlos en un mismo directorio

Ejecutar el Dockerfile asegurandose que el **xstartup** esté en el mismo directorio, para crear la imagen:

docker build -t "NOMBRE DE LA IMAGEN" ./Dockerfile

una vez tengamos la imagen, para crear el contenedor ejecutamos el siguiente comando:

docker run -d -p 2222:22 -p 5901:5901 "NOMBRE DE LA IMAGEN"

Para conectarse a través de VNC  se deberá de utilizar un cliente VNC a través del puerto 5901.
