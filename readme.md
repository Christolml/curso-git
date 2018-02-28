## Curso git desde cero

##Zonas de git
1- Directorio de trabajo
2-Área de preparación
3-Directorio de git

##comandos iniciales para git para consola
git init => es para inicializar git y empezar a guardar los cambios desde la ruta de una carpeta
en nuestra terminal

git status => es para ver como se encuentran nuestros archivos de nuestra carpeta en donde estamos ejecutando git

git add "file name" => con este agrego a mi git los archivos que quiero que se guarden

git commit -m "Mensaje descriptivo del commit"  => con esto ya confirmo los cambios que he hecho en mi carpeta git y con esto se va creando puntos de respaldo de tiempo

gt log => con este puedo ver los commits realizados, quien los hizo sus versiones, su fecha y el mensaje del commit

git diff => muestra lo que se ha modificado en nuestro git

git commit --amend => con este puedo editar un comentario

##Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos
git add .  => para agregar varios archivos a la vez es sin importar si estamos siguiendo

git reset HEAD "file name" => es para quitar mi archivo de la zona de preparación y volverla al Directorio   de trabajo

git add -A => con este agrega todos los archivos que estan en el directorio de trabajo y que estemos ya siguiendo con git
