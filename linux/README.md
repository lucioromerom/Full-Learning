Linux





TERMIANL GIT
Comandos Git útiles:
. git init : crea las carpetas git necesarias (no se modifican)
. git add . : prepara todo para antes del commit, guarda los cambios locales
. git reset . : va despues del add, es por si no esta "listo" para el commit
. git commit -m "mensaje" : guarda todo hasta el momento, con un mensaje
. git checkout -- . : todos los archivos vuelven a como estaban antes del último commit
. git log : listado de los commits
. git commit --amend : arregla el último commit ----> tecla "i" para ingresar texto, tecla "Esc", "w" (write), "q" (quit), "!" (salir/guardar inmediatamente)
. git checkout -b nombre-rama : creas una rama y le pones el nombre 
. git checkout master : te pasas a la rama "master", la "principal"
. git branch -d nombre-rama : borras esa rama
. git branch : ves las ramas 
. git branch -M main : nombras la "master" como "main
. git remote add origin https... : origin es el nombre remoto del repositorio, https(link del repositorio), conectar tu cuenta (por token?)
. git push -u origin main : la primera vez, para guardarlo en github
. git push : una vez hecho el push -u origin main, haces solo git push
. git commit -am "mensaje" : es el git add . y el git commit -m "" en un solo comando
. git status : para ver todos los archivos que se van a guardar/confirmar en el push

