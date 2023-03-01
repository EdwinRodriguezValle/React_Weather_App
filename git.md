con#Pasos para seguir en git #

1. En tu proyecto iniciar git con el comando.
## git init ##

2. crear el archivo .gitignore en tu proyecto.
## .gitignore ##

3. Crear un repositorio en la plataforma.
##conectar el SSH del repositorio y los datos que ahí muestra al crear el repo ##

4. Chequear
## git status ##

5. para agregar un repositorio al proyecto
## git remote add origin + nombre del SSH del repositorio creado ##

6. Para cambiar origen y crear un nuevo branch
## git remote rm origin ##
esto debe dar un blanco

7. Para agregar una nueva rama o branch
## git checkout -b + más nuevo nombre del branch ##

8. Para agregar
## add . ##

9. Para commentar
## git commit -m ##

10. Para subir los archivos
## git push origin + nombre de la rama o directamente al origen ##

11. En la plataforma de git hacer los siguiente
## Aceptar el pull request y hacer los comentarios o reviciones ##
## Si todo esta bien hacer un merge con el boton merge ##

12. Volver al proyecto y hacer un pull para actulizar
## git pull ##

13. Si estas trabajando con otro, entonces una vez que el otro a comentado y le has revisado y el
    acepta los comentario y hace el marge, hay que hacer lo siguiente
## git pull main ## [para actualiar]

14. Luego puedes borrar el rama en la que estabas trabajando.
## git + nombre de rama + -d ##
{sino borra forzar con -D}

15. Para chequear el branch
## git branch ##

16. por lo de más buscar en internet. Se puede hacer muchas cosas por ahí

17. para cambiar al main
## git switch main ##

18. pull the main la última versión actualizada
## git pull the main ##

19. La idea de git es crear un repositorio, subir un proyecto ahí, crear ramas de trabajos uno o varios,
en seguida, cargar a las ramas todo lo que has trabajado, cuando ha sido revisado por un tercero
hacer la fusión o merge, después de fucionar para que se convierta en la matriz principal, ese punto de tiempo jalar a tu ordenador para
trabajar sobre esa versión, subir, revisar y bajar y de esa manera todo el proyecto.
