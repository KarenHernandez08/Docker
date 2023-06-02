# Docker

[Curso](https://github/KarenHernandez08/Docker)

`Docker` es una plataforma de software que permite crear e implementar aplicaciones rapidamente, `Docker` empaqueta siftware en unidades estandarizadas llamadas contenedores que incluyen todo lo necesario para que el software se ejecute incluyendo bibliotecas, como librerias, herramientas de sistema, código y tiempo de ejecución.

![imagen de el logo de docker](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/Docker.png)


### Contenidos

- [Introduccion a Docker](https://github.com/KarenHernandez08/Docker#introducci%C3%B3n-a-docker)
- [Instalación Docker](https://github.com/KarenHernandez08/Docker#instalaci%C3%B3n-a-docker)
- [Instalación Docker en Linux](https://github.com/KarenHernandez08/Docker#instalaci%C3%B3n-docker-en-linux)
- [Instalación Docker en windows](https://github.com/KarenHernandez08/Docker#instalaci%C3%B3n-docker-en-windows)
- [Primera Imagen](https://github.com/KarenHernandez08/Docker#primera-imagen)

## Introducción a Docker
Para comenzar con nuestro primer proyecto vas a ir a [Play with Docker](https://labs.play-with-docker.com/)

Donde vamos a:
- Iniciar sesión, en caso de no tener, vamos a crear un nuevo usuario
- Añadimos una nueva instancia

En la terminal escribiremos el siguiente comando para crear nuestra ballenita Docker
```
$ docker run docker/whalesay cowsay boo
```
Nota
> En el comando anterior, boo puede ser cambiado por cualquier otro texto

Asi se mostrara nuestra ballena con Play with Docker

![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/dockerweb.PNG)



## Instalación a Docker
### Instalación Docker en Linux 
 En mi caso la instalación de docker fue en la terminal con los siguientes comandos
``` 
sudo apt update

sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo add-apt-repository \"deb [arch=arm64] https://download.docker.com/linux/ubuntu \$(lsb_release -cs) \stable"

sudo apt update

sudo apt-get update

sudo apt-get install docker-ce docker-ce-cli containerd.io

sudo apt-get install docker-ce

sudo apt  install docker.io 

sudo snap install docker

sudo usermod -aG docker ${USER}

su - ${USER}
 
 ```
 
 Verificamos que se installo, viendo la versión de docker que tenemos
 
  ```
  docker --version

```
Por ejemplo yo tengo instalada la version `20.10.7`
![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/version.PNG)

### Instalación Docker en Windows

## Primera imagen
Para realizar este ejercicio me ayudo el ver este [video](https://www.youtube.com/watch?v=-733YUqd2sM&ab_channel=FaztCode)

clonamos el siguiente repositorio en nuestra terminal 

```git

git clone https://github.com/dockersamples/node-nulletin-board

```

Lo demas esta dentro de las imagenes siguientes de la consola y al finalizar nuestra imagen corriendo 

![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/docker%20image.PNG)
![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/docker%20image%201.PNG)
![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/docker%20image2.PNG)
![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/docker%20image%203.PNG)
![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/docker%20image%204.PNG)
![](https://github.com/KarenHernandez08/Docker/blob/main/imagenes/docker%20image%205.PNG)

---

# DOCKER

Docker es una plataforma de software que nos permite crear y probar aplicaciones rapidamente a través de docker.

`Contenedor` lugar que sirve para almacenar algo.

Docker funciona a través de una arquitectura cliente-servidor

descargar docker desde el siguiente enlace https://docs.docker.com/get-docker/

Para verificar que tenemos docker instalado colocamos en nuetra terminal `docker --version`

Si colocamos `docker` en la terminal se nos desplegan todos los comandos disponibles de docker.

`docker image` comando que nos va a ayudar para nuestras imagenes

`docker image pull <NombredeImagen>` para descargar las imagenes de docker 

### Hola Mundo en docker