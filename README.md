# curso-git-github
Curso de GIT y git Hub

## Colaborar en un proyecto open source GitHub

1. Fork del repositorio
2. Clonar Repositorio `git clone urlRepositorio`
3. Entrar a la carpeta clonada `cd carpetaClonada` 
4. Verificar conexiones remotas `git remote -v`
5. Agregar conexión remota al repositorio original `git remote add upstream urlRepositorioOriginal`
6. (Opcional) Renombrar conexion remota `git remote rename origin fork`

## Trabajo diario
1. Actualizar rama master con ultimos cambios `git pull -r upstream main`
2. Crear requerimiento (issue GitHub)
3. Crear rama donde se desarrollara la funcionalidad `git checkout -b feature-nombre-rama`
4. Trabajar en el codigo (Podemos usar `git status` para ver los archivos que han cambiado)
5. Agregar al stage `git add .`
6. Commit de los cambios `git commit -m "Descripción del avance" ` 
7. Subir ramas con los cambios `git push origin feature-nombre-rama`
8. Solicitar que se incorporen cambios en el proyecto original **Pull Request**
9. Eliminar rama local `git branch -d feature-nombre-rama`
10. Eliminar rama en repositorio remoto `git push origin --delete feature-nombre-rama`
11. Unir Ramas `git merge feature-nombre-rama`
