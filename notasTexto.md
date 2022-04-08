# Comandos para crear un repositorio local git y luego vincularlo a Git Hub
mkdir: nos permite crear carpetas, p. ej. mkdir NuevaCarpeta - creamos la carpeta local
git init . iniciar repositorio git, se crea el archicvo oculto que se ve con ls -a
$ git config --global init.defaultBranch main - asi trabajamos directamente en la rama main por defecto
touch: nos permite crear archivos nuevos, p.ej. touch NuevoArchivo.txt
git config --global user.name "name"
git config --global user.email "email"
git status
git add nombredelarchivo
git commit -m "Comentario"
git status
crear repositorio en git hub - sacar el link
git remote ad origin https://..
git remote -v
el repositorio remoto esta vacio
git push origin master

luego hay que migrar la rama master a la rama main
git status - vemos que estamos en la rama master
git branch -m master main
git branch - comprobamos que estamos en main
git push -u origin main
git symbolic -ref 

# Otros comandos utiles
cat: nos permite ver el contenido de un archivo, p.ej. cat NuevoArchivo.txt
cd: nos permite cambiarnos de carpeta, p.ej. cd NuevaCarpeta.
cd .. : nos permite regresar al directorio o carpeta anterior.
cd o cd ~: nos lleva a la ruta del usuario.
cd /c: nos vamos al disco C:/.
cd -: nos lleva directamente al ultimo directorio visitado.
ls: nos permite ver los archivos de la carpeta donde estamos actualmente.
ls -a
rm: Nos permite borrar un archivo o carpeta ej: rm NuevoArchivo.txt
clear: nos permite limpiar la pantalla.
history: ver los últimos comandos que ejecutamos y un número especial con el que podemos volver a repetir el comando.