# Hadoop-BigData-Docker

## Ejecución

En la máquina con Docker se hace un `docker login` y luego:

```bash
git clone https://github.com/luisangelzerocool/Hadoop-BigData-Docker.git

cd Hadoop-BigData-Docker
``` 

Ejecutar el comando `./start-cluster.sh`

>En caso que salga error de permisos al ejecutar, se ejecuta el comando `chmod 700 start-cluster.sh`

## Resultados

En el bash se vería algo como esto:

![Resultado](/screenshots/1.png)

Luego si vamos a la dirección `http://192.168.1.13:50070/`

>Veríamos algo así:

![Resultado](/screenshots/2.png)

Luego si vamos a la dirección `http://192.168.1.13:8088/` 

>Veríamos algo así:

![Resultado](/screenshots/3.png)

