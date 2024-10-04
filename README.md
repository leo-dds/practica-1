# practica-1
**docker pull nome_imaxen**: sirvenos para descagar unha imaxen para o noso docker 

**docker images**: poderemos ver todas as imaxes que temos no docker 

**docker run -d nome_imaxen**: creamos e arancamos o contenedor 

**docker ps -a**: comprobamos que se arrancara corectamente e podemos ver o resto de contenedores que estan arrancados. 

**docker run -d --name u1 ubuntu**: creamos un contenedor chamado _"u1"_

**docker exec -it u1 bash**: unha vez teñamos o contenedor arrancado poderemos acceder a el.

**hostname -I**: sirvenos para comprobar cal e a ip do noso contenedor que neste caso e _172.17.0.2_

**docker run -d --name bono ubuntu**: para crear el otro contenedor para hacer pin, vemos que su ip es _172.17.0.3_ y al hacerle ping al otro contenedor si que nos contesta.


Cando pechamos o terminal podemos comprobar con **docker ps -a** que o contenedor detuvose 

**docker system df**: comprobamos canto do disco esta ocupado, neste caso as imaxes ocupan _92MB_ y los conrainers _49B_

**docker stats**: lograremos ver canta RAM ocupa os nosos contenedores que esten arrancados.Os contenedores cupan mais ou menos _900KiB_

 **git clone https://github.com/leo-dds/practica-1.git** : es el comando co que puiden clonar o repositorio no meu equipo 
 
 Con calquel editor de texto poderemos añadir dentro do repositorio un archivo de texto. 
 
 Los pasos a seguir para subir el archivo son:
 Primero hacemos un **GIT ADD README.md** para preprar el archivo para ser subido 
 
 Segundo **GIT COMMIT -m** para añadir un comentario y saber donde nos quedamos en la ultima subida 
 
 Por ultimo **Git PUSH** para subir el archivo 
 
Para poder comprobar las diferencias del repositorio local y remoto lanzamos los comandos:

**git status** para ver los cambios pendientes de enviar 

**git fetch y git diff origin/main** para comprobar el repositorio local del remoto 
