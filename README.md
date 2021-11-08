En este modulo cero, aprendimos lo siguiente:
Comando básicos de Linux:
pwd Me permite conocer la ruta actual (Donde estoy ubicado).
ls ver los elementos de la carpeta donde estoy ubicado.
clear Limpiar la pantalla.
ls -la Ver detalle de la información con los permisos que tienen esos recursos.
mkdir crear un directorio.
rm – rf [nombre directorio]: Borrar de forma forzosa el recurso.
cd [carpeta]: dirigirme a una carpeta deseada.
cd .. devolverme a una ruta o carpeta anterior.
touch [NombreNuevoArchivo] : crear un archivo de cualquier tipo distinto a una carpeta.
nano [NombreNuevoArchivo] : Crear un archivo.

Tambien aprendimos a diferenciar GIT de GITHUB
Su configuración, como lo indicamos acontinuación:
git config --global user.name <name> : define el nombre que se va a utilizar en los commits de forma global (para el usuario actual).
git config --global user.email <email> : define el correo electrónico que se va a utilizar en los commits de forma global (para el usuario actual).
git config --global -e : comando para verificar la información de la configuración
git init : este comando se encarga de iniciar el repositorio (esto va a crear una carpeta oculta .git en la carpeta donde ejecutes este comando).
git add . : prepara los archivos para el commit .
git commit -m <descripción de los cambios> : crea un commit a partir de los cambios que están en el index con el mensaje que se le pase a la opción -m .
git status : muestra la lista de archivos con cambios desde el último commit y los que van a ser incluídos en el siguiente commit.
git remote add origin <url repositorio> : Indicar la dirección del repositorio
git push origin <Raman main> : Entregar los cambios
git pull origin <Raman main> : Bajar los cambios

Por ultimo conocimos las Instrucciones básicas MarkDown.