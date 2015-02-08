Hola Mundo {EDITANDO ESTE ARCHIVO EN NUEVO BRANCH} UN NUEVO DIA Y UN NUEVO ACCESO PARA NO PERDER LA COSTUMBRE

Esta es la documentación que he añadido a la información tipada anteriormente.

Comandos utilizados hasta el momento:


Git Bash
cd <directorio> para moverse
cd solo para ir para atras
git branch <nombre> para crear una branch, rama
git checkout -b <nombre branch> para crear una branch y saltar a ella directamente
git branch para listar branchs
git branch -d <nombre branch para eliminar branch"
git branch -a para mostrar directorios ocultos
git branch -v te muestra los últimos commits en cada branch dentro del directorio
git checkout para moverse entre branchs
git config --global afecta a todo el entorno del usuario
git merge <nombre branch> para fusionar branch al repositorio donde estamos ubicados
ls para comprobar archivos y directorios en una carpeta
git init para iniciar la actividad de git en una carpeta
git add -A para colocar en el disparadero y hacer commit
git commit -am "texto descriptivo del cambio" para añadir, realizar cambio y aportar mensaje
git push origin master para subir commit local a repositorio github
touch <archivo.txt> crea un archivo en el repositorio local
mkdir <nombre> para crear directorios, carpetas
git fetch origin si no me equivoco, envia los datos del repositorio remoto al repositorio oculto origin/master
git merge origin/master para fusionar repositorio oculto con repositorio local y obtener los cambios realizados en remoto en nuestro repositorio local

AÑADIDO: origin/master rama intermedia oculta, que deberemos fusionar con master para sincronizar datos modificados en remoto
a nuestro repositorio local

paso correcto para añadir cambio de un archivo git local a github
creación o modificación del archivo o en sublime o en consola con touch 
GUARDAMOS vamos a consola git bash
hacemos un git status para comprobar el cambio en el archivo si lo ha detectado git y procedemos con:
git add -A o bien, podemos acortar con git commit -am "nuestro mensaje" para añadir el archivo, 
hacer commit con el archivo en nuestro repo local y dejar el comentario descriptivo de nuestro archivo, 
cambio o adición.
seguidamente, para subir los cambios y hacer commit con los archivos remotos de github, tenemos que aplicar el comando
git push origin master

Ahora la tarea es hacerlo a la inversa, meterme en github de nuevo, crear o modificar un archivo existente, y enviar los cambios a mi repositorio local.

tan sencillo como ir a github, modificar el archivo que habia creado y darle extensión a .txt, y añadirle algo de texto, descripción del cambio y commit desde github
entonces, seguidamente aplico el comando git fetch origin y seguidamente git merge origin/master para sincronizar con mi repositorio local y obtener los cambios, 
me ha funcionado, así que :)

CREACIÓN DE UN ALIAS PARA ACORTAR COMANDOS CON GIT
Para crear un alias, por ejemplo para mostrar de manera visual el log de commits y branchs sin tener que escribir el comando largo 
git log --graph --decorate --oneline podemos crear un alias de manera sencilla, aunque es recomendable conocer bien el 
comando y estar muy acostumbrado a su uso para decidir acortarlo en un alias y olvidarnos de su practica, es por eso que 
para principiantes como yo en este momento no es necesario, sin embargo, voy a hacer uno para poner en practica la clase con Mike Nieva de Platzi

lo que hice fue llamar a git config --global alias.vision "log --graph --decorate --oneline", ahora, solo tengo que poner git vision para obtener 
el resultado del comando largo mencionado anteriormente, muy útil y seguro que tendré que acostumbrarme a ello si decido seguir con este sistema, aunque
sinceramente, soy del paleolítico y aún me manejo más cómodo por el momento con FTP, veremos de aquí a final de curso :D

Saludos si es que hay alguien que va a leer este parrafo