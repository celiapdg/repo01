## C1 Git y Github. Ejercicio 1
1. Crear la carpeta **repo01**
2. Entrar en la carpeta, clic derecho y abrir Git Bash en esa ubicación
3. usar el comando `git init`
4. Abrir la carpeta en VS Code, crear el archivo .md (o .markdown)
5. Hasta ahora estábamos en el estado "Working Directory", vamos a pasar a la "Staging Area" con el comando `git add .`
6. Hacemos un snapshot al repositorio local con `git commit -m "initial commit"`
7. Entramos en GitHub y creamos un repositorio desde ahí, también llamado **repo01**.
8. Copiamos el enlace a este repositorio, para luego vincular los repositorios local y remoto utilizando el comando `git remote add origin https://github.com/celiapdg/repo01.git`
9. Para que el repositorio remoto contenga los cambios realizados en el repositorio local, haremos un push a la rama master `git push -u origin master`

Si ahora nos dirigimos al enlace del [repositorio](https://github.com/celiapdg/repo01), veremos que el readme está actualizado en la web.