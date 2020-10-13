# 2.2- Instalación del servidor web Apache en Ubuntu Server
## 1. Instalar Apache.
1.1.- ejecuro sudo apt update para actualizar los binarios del repositorio de ubuntu

![punto1.1-img1](img/punto1.1-img1.png)

1.2.-ejecuto apt install apache2

![punto1.2-img2](img/punto1.2-img1.png)

## 2. Configurar el firewall.

2.1.- ejecuto el comando sudo ufw app list 

![punto2.1-img1](img/punto2.1-img1.png)

2.2.- ejecuto sudo ufw allow 'Apache'. Compurebo el estado del firewall con sudo ufw status y lo activo con sudo ufw enable

![punto2.2-img1](img/punto2.2-img1.png)

## 3. Comprobar el estado del servidor web.

3.1.- compuebo que apache esta levantado con sudo systemctl status apache2

![punto3.1-img1](img/punto3.1-img1.png)

tambien es accesible desde la red

![punto3.1-img2](img/punto3.1-img2.png)






