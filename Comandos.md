| **Categoría**             | **Comando**                                    | **Descripción**                                                                 |
|---------------------------|-----------------------------------------------|-------------------------------------------------------------------------------|
| **Configuración**         | `git config --global user.name "Tu Nombre"`   | Configura el nombre de usuario para Git.                                      |
|                           | `git config --global user.email "email"`      | Configura el correo electrónico para Git.                                     |
|                           | `git config --list`                          | Muestra la configuración actual.                                              |
| **Inicialización**        | `git init`                                   | Inicializa un nuevo repositorio Git.                                          |
|                           | `git clone <URL>`                            | Clona un repositorio remoto a tu máquina local.                               |
| **Gestión de archivos**   | `git status`                                 | Muestra el estado de los archivos en el repositorio.                          |
|                           | `git add <archivo>`                          | Añade un archivo al área de preparación.                                      |
|                           | `git add .`                                  | Añade todos los archivos modificados al área de preparación.                  |
|                           | `git rm <archivo>`                           | Elimina un archivo del repositorio y del área de preparación.                 |
| **Confirmar cambios**     | `git commit -m "Mensaje"`                    | Guarda los cambios con un mensaje descriptivo.                                |
|                           | `git commit -a -m "Mensaje"`                 | Salta la etapa de `git add` y confirma todos los cambios rastreados.          |
| **Visualización**         | `git log`                                    | Muestra el historial de commits.                                              |
|                           | `git log --oneline`                          | Muestra el historial en un formato compacto.                                  |
|                           | `git log --graph --decorate --oneline`       | Muestra un gráfico de ramas con el historial.                                 |
| **Ramas**                 | `git branch`                                 | Lista las ramas existentes.                                                   |
|                           | `git branch <nombre>`                        | Crea una nueva rama.                                                          |
|                           | `git checkout <nombre>`                      | Cambia a una rama existente.                                                  |
|                           | `git checkout -b <nombre>`                   | Crea una nueva rama y cambia a ella.                                          |
|                           | `git merge <rama>`                           | Fusiona la rama especificada con la actual.                                   |
|                           | `git branch -d <rama>`                       | Elimina una rama.                                                             |
| **Remotos**               | `git remote add origin <URL>`                | Asocia un repositorio remoto llamado "origin".                                |
|                           | `git remote -v`                              | Lista los repositorios remotos configurados.                                  |
|                           | `git fetch <origen>`                         | Descarga los cambios del repositorio remoto sin fusionarlos.                  |
|                           | `git pull <origen> <rama>`                   | Descarga y fusiona los cambios del repositorio remoto con la rama actual.     |
|                           | `git push <origen> <rama>`                   | Sube los cambios locales a una rama del repositorio remoto.                   |
| **Deshacer cambios**      | `git reset <archivo>`                        | Elimina un archivo del área de preparación.                                   |
|                           | `git reset --soft HEAD~1`                    | Deshace el último commit pero mantiene los cambios en el área de preparación. |
|                           | `git reset --hard HEAD~1`                    | Deshace el último commit y elimina los cambios del área de trabajo.           |
|                           | `git revert <commit>`                        | Crea un nuevo commit que deshace los cambios de un commit anterior.           |
| **Etiquetas**             | `git tag`                                    | Lista todas las etiquetas en el repositorio.                                  |
|                           | `git tag -a <versión> -m "Mensaje"`          | Crea una etiqueta anotada.                                                    |
|                           | `git push origin <etiqueta>`                 | Sube una etiqueta específica al repositorio remoto.                           |
| **Stash**                 | `git stash`                                  | Guarda los cambios actuales sin confirmar de forma temporal.                  |
|                           | `git stash list`                             | Lista los cambios guardados en el stash.                                      |
|                           | `git stash apply`                            | Restaura los cambios guardados en el stash sin eliminarlos.                   |
|                           | `git stash pop`                              | Restaura y elimina los cambios del stash.                                     |
