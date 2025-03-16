# docker-rvm_ypb
#Hecho por Yohancel Pita y Rowan Vowler

# Pasos a seguir

Descargar los archivos del repositorio y ponerlos en un mismo directorio

Ejecutar el Dockerfile asegurandose que el **xstartup** esté en el mismo directorio:

docker build -t "NOMBRE DE LA IMAGEN" ./Dockerfile

El objetivo de este Dockerfile es crear una imagen basada en Ubuntu 24.04 que contenga un entorno de visualización (VNC) por el cual se pueda utilizar VScode el cual se inicia automaticamente.
