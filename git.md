# Ordenes básicas de git

| Comando                                    | Descripción                                                                  |
|--------------------------------------------|------------------------------------------------------------------------------|
| `git config --global user.name "nombre"`   | Configura el nombre que aparecerá en los commits                             |
| `git config --global user.email "email"`   | Configura el correo electronico que aparecerá en los commits                 |
| `git config --gloval core.editor "editor"` | Configura el editor por defecto en git                                       |
| `git init`                                 | Inicializa un nuevo repositorio en la carpeta actual                         |
| `git clone [url]`                          | Descarga un repositorio remoto a la carpeta actual                           |
| `git status`                               | Muestra los archivos nuevos o modificados                                    |
| `git diff [rama 1] [rama 2]`               | Muestra diferencias entre ramas                                              |
| `git add [file]`                           | Mueve el archivo al area de preparacion                                      |
| `git commit`                               | Registra los cambios del area de preparación en la versión final del archivo |
| `git branch [nombre-rama]`                 | Crea una nueva rama                                                          |
| `git branch -d [nombre-rama]`              | Borra la rama especificada                                                   |
| `git branch`                               | Muestra las ramas en el repositorio actual                                   |
| `git checkout [nombre-rama]`               | Cambia a la rama especificada                                                |
| `git merge [nombre-rama]`                  | Combina la rama especificada con la rama actual                              |
| `git log`                                  | Muestra el historial de versión de la rama actual                            |
| `git push` [alias] [rama]                  | Carga todos los comits de la rama local a la remota                          |
| `git pull`                                 | Descarga el historial del remoto y incorpora los cambios                     |