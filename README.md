# apuntesGit
Apuntes extraídos del video de MoureDev en youtube

> Que es GIT:  
    Es un sistema de control de versiones distrivuidos de ficheros.
    Aparecio el 7 de abril de 2005, uno de sus creadores es Linux Torval

    Que es un sistema de control de versiones?
    Es una herramienta que gestiona cambios en el código fuente de un proyecto, permitiendo rastrear las modificaciones.
    El siguiente es un ejemplo: [main 995dce8], se puede observar que sobre la rama main se tiene el hash 995dce8, el mismo es unico e irrepetible, durante todo el proyecto.


**CONFIGURACION DE USUARIO DE GIT**
* git config --global user.name "tuUserName"
* git config --global user.email "tuUseremail"


**COMANDOS POR TERMINAL**  
* ls : lista los directorios que son alcanzados por git.
* cd : sirve para desplazarnos entre los ficheros.
* pwd : nos indica donde estamos.
* mkdir "name folder" : crea un nuevo directorio.
* git init : inicializar git dentro del directorio creado.
* git status : nos muestra las modificaciones en los archivos alcanzados por git.
* git add nombreArchivo : adherir para realizar seguimiento a un archivo específico.
* git add . : adherir todo lo que esta al alcanse de git.
* git commit -m : guarda una especie de instantanea del proyecto en ese momento y nos indica que tenemos que agregar un mensaje
* git log : nos muestra los registros comiteados.

>
    Que es una rama "branch"?  
    Es una línea de desarrollo independiente que permite trabajar cambios de forma aislada. Permite crear y funsionar nuevas características, sin afectar a la rama principal.