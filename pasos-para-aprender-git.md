Los pasos para aprender Git:

1. Iniciar el trackeo con git init.

2. Añadir archivos con:
   - git add <archivo> (para archivos específicos)
   - git add . (para todos los archivos)

* Si deseas eliminar archivos del staging (area de carga para commit):
  - git rm --cached (para eliminar del área de staging)
  - git rm --forced (para eliminar de forma permanente)

3. Preparar archivos para publicar al repositorio con git commit -m <mensaje>

4. git clone <url> para clonar el repositorio local a un repositorio remoto (GitHub, GitLab, etc.)

5. git push para enviar el HEAD del (master), o sea el último commit al repositorio remoto

* Si deseas traer algún archivo del repositorio remoto al repositorio local usa git fetch
  Para trabajar con el archivo, necesitarás mover el archivo del "repositorio local" hacia tu "directorio de trabajo", es decir hacia tu carpeta de trabajo; para eso usa git merge

  Se puede omitir git fetch y git merge con git pull