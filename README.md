## Comandos básicos de GIT

Verificar estado del repositorio
    git status


Preparar archivos
    git add <file>
    git add -A "se para en el root del directorio y toma todos los archivos hijos"
    git add . "busca archivos desde el directorio a los hijos"
    git add *.html "comodin para archivos con la extensión"


Guardar archivos en el repositorio local
    git commit -m "descripción de los cambios hechos al proyecto"


Enviar proyecto al repo remoto
    git push origin master/main