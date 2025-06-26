# COMANDOS GIT

- git init: inicializa git en un proyecto.
- git remote add origin [enlace repo]: Conecta un proyecto con un repositorio.

## Preparamos nuestros cambios para ser enviados al repositrio.
- git add [nombre achivo]: Registra un archivo para ser enviado al repo.
- git add . : Registra todos los archivos.

## Preparamos el backup
- git commit -m [nombre commit]: Prepara una version segura a la cual podemos volver (un backup).

## Enviamos las actualizaciones al repo
- git push: Envia las actualizaciones a una rama generica
- git push origin [nombre rama]: Envia las actualizacions a una rama origen (default)

## Para revisar informacion
- git status: Revisamos que esta registrado y que no. (rojo: no registrado. Verde: Registrado)
- git log: revisamos la lista de commits realizados. (El que tiene el HEAD es el ultimo y apunta a la rama en la cual se realizó.)