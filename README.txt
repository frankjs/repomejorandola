Hola Mundo

Esta es la documentación que he añadido a la información tipada anteriormente.

Comandos utilizados hasta el momento:

Git Bash
cd <directorio> para moverse
cd solo para ir para atras
git branch <nombre> para crear una branch, rama
git branch para listar branchs
git branch -d <nombre branch para eliminar branch"
git branch -a para mostrar directorios ocultos
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
