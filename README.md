# practica-1
docker pull nome_imaxen: sirvenos para descagar unha imaxen para o noso docker 

docker images: poderemos ver todas as imaxes que temos no docker 

docker run -d nome_imaxen: creamos e arancamos o contenedor 

docker ps -a: comprobamos que se arrancara corectamente e podemos ver o resto de contenedores que estan arrancados. 

docker run -d --name u1 ubuntu: creamos un contenedor chamado "u1"

docker exec -it u1 bash: unha vez teñamos o contenedor arrancado poderemos acceder a el.

hostname -I: sirvenos para comprobar cal e a ip do noso contenedor que neste caso e 172.17.0.2

docker run -d --name bono ubuntu: para crear el otro contenedor para hacer pin, vemos que su ip es 172.17.0.3 y al hacerle ping al otro contenedor si que nos contesta.
