## Pasos para generar nuestro repositorio de notas en GitHub

Crear un repositorio nuevo en git hub con el nombre "NotasProgramacion". Seleccionando la opcion de crear archivo README.
Hacer una copia para tenerlo de forma local en nuestra maquina. Copiamos en en lace y creamos el repositorio usando el comando $ git clone.
Seteamos por defecto para trabajar en la rama main con el comando $ git config --global init.defaultBranch main
Creamos dos archivos de nombre CrearRepositorio.md y notasJavaScrpit.js utilizando el comando touch.
Pasamos a stage a los archivos utilizando el comando $ git add
Comiteamos los archivos usando el comando $ git commit -m "comentario"
Subimos nuestro repositorio local a Git Hub utilizando $ git push origin main
Nuestro repositioro estara creado y listo para ser utilizado.

## Otras configuraciones adicionales
git config --global user.name "name"
git config --global user.email "email"

## Resumen de comandos
mkdir: nos permite crear carpetas, p. ej. mkdir NuevaCarpeta - creamos la carpeta local
touch: nos permite crear archivos nuevos, p.ej. touch NuevoArchivo.txt
git add nombredelarchivo
git commit -m "Comentario"
git status
git push origin master
git branch -m "rama1" "rama" para cambiar de rama
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