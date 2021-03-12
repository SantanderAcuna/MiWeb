Comando para configurar el usuario y email de git 

git config --global user.name "SaCunaPolo"
git config --global user.email "panson@misena.edu.co"
/***************************************************************************************************/
COMANDO PARA VER LAS CONFIGURACIONES REALIZADAS EN GIT 

git config --global -e

COMANDO PARA LISTAR LOS CAMBIOS REALIZADOS EN GIT

git config --global -l

/***************************************************************************************************/


git status  Comando para ver los estados de los cambios
git status -s Comando para ver los estados de los cambios mas organizados
git status -s -b Comando para ver los estados de los cambios mas organizados y en la rama que me encuentro actualmente

git log comandos para saber los cambios realizados
git log --oneline comandos para saber los cambios realizados pero de una manera mas organizada
git log --oneline --decorate --all --graph
/***************************************************************************************************/
CREAR ALIAS EN GIT

git config --global alias.lg "log --oneline --decorate --all --graph"
git config --global alias.s "status -s -b"


/***************************************************************************************************/


git checkout -- .  Comando para restaurar el proyecto al ultimo commit

/***************************************************************************************************/
Algunos en la próxima clase han presentado este problema con el CRLF, no es nada serio, es básicamente una interpretación de un caracter.

Simplemente ejecuten este comando si presentan el error:

git config core.autocrlf true

/***************************************************************************************************/
comando para listar los archivos que se encuentran en la carpeta

ls lista todos los archivos de una carpeta
ls -al lista todos los archivos de una carpeta y tambien muestra el archivo .git


Comando para agregar todos los archivos al stage

git add -A
git add .
git add --all
git add "*.txt" Agrega todos los txt de todo el proyecto
git add *.txt Agrega todos los txt en el directorio actual
git add "*.txt" Agrega todos los txt de todo el proyecto
git add <lista de archivo> Se pueden agrgar varios archivos al mismo tiempo separados por un espacio
git add pdf/*.pdf Agrega todos los archivos con extencion pdf de la carpeta


Comando para excluir archivos del stage 
git reset * (Mas el nombre de la extension )
eje: git reset *xml








