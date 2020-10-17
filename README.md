# LAB-SA-Practica10
## José Manuel Véliz Sandoval - 201602959
Esta rama contiene la práctica #10 del curso de software avanzado, la cual consiste en utilizar docker, docker-compose para desplegar el software desarrollado en la practica #7. Esto haciendo uso de volumenes y creación de imágenes.

## Practica #7
[Repositorio](https://github.com/CiberVeliz/LAB-SA-Practica5)

## Versiones de herramientas utilizadas
- Docker: 19.03.6, build 369ce74a3c
- Docker-compose: 1.21.2, build a133471

## Ejecución del .yaml
Para crear las imagenes y levantar los servicios solo es necesario correr el siguiente comando:
```
sudo docker-compose up -d
```
o
```
sudo docker-compose up
```
Y para tener la ejecución, ya se Ctrl + C o el siguiente comando:
```
sudo docker-compose down
```
Si en ninguno de los pasos anteriores ocurrió un error, se debería de visualizar los 3 microservicios y el ESB en los puertos especificados en el .env.

## Video
[Explicación](https://drive.google.com/file/d/1XkC4z3fWFT-xjsyJA4ggQ2AUw3Yj5M7s/view?usp=sharing)
