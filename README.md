# tp20210117


1- Instancier un container redis 


2- Faire tourner l app et voir qu est ce qu il y a dedans 


3- Comment écrire un fichier Docker Compose 


4- Quelle service doivent avoir ? 

version: '3'
services:
  web:
    build: .
    ports:
     - "5000:5000"
  redis:
    image: "redis:alpine"


5- Comment doivent etre communiqué entre eux? 

6- Est-ce que j'ai besoin un DockerFile pour tourner ces deux apps ? 

7- Comment communiquer 2 service avec Docker compose? 

8- Comment y acceder ?