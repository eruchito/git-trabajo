# git-trabajo

¿Qué es GitHub?
GitHub es una plataforma de desarrollo colaborativo que permite alojar repositorios Git de manera remota. Permite la gestión de código fuente, control de versiones y facilita la colaboración entre desarrolladores.

¿Cómo crear un repositorio en GitHub?
Para crear un repositorio en GitHub:
Inicia sesión en GitHub.
En la página de inicio, haz clic en el botón New repository.
Asigna un nombre, descripción y elige si será público o privado.
Haz clic en Create repository.

¿Cómo crear una rama en Git?
Para crear una rama en Git:
git branch <nombre_de_la_rama>

¿Cómo cambiar a una rama en Git?
Para cambiar a una rama en Git:
git checkout <nombre_de_la_rama>

¿Cómo fusionar ramas en Git?
Para fusionar una rama a la rama activa:
Cambia a la rama donde deseas fusionar (ejemplo: main).
Ejecuta:
git merge <nombre_de_la_rama>
¿Cómo crear un commit en Git?

Para crear un commit, primero agrega los archivos modificados al área de preparación (staging):
git add <archivo>
Luego crea el commit con:
git commit -m "mensaje del commit"

¿Cómo enviar un commit a GitHub?
Para enviar el commit a GitHub (es decir, hacer push), usa:
git push origin <nombre_de_la_rama>

¿Qué es un repositorio remoto?
Un repositorio remoto es una versión del repositorio que está alojada en un servidor o servicio de nube como GitHub, GitLab o Bitbucket. Sirve para colaborar y mantener el código accesible desde diferentes ubicaciones.

¿Cómo agregar un repositorio remoto a Git?
Para agregar un repositorio remoto:
git remote add origin <url_del_repositorio>

¿Cómo empujar cambios a un repositorio remoto?
Para empujar cambios, usa el comando:
git push origin <nombre_de_la_rama>

¿Cómo tirar de cambios de un repositorio remoto?
Para tirar de cambios desde un repositorio remoto, usa:
git pull origin <nombre_de_la_rama>

¿Qué es un fork de repositorio?
Un fork es una copia personal de un repositorio que permite hacer cambios sin afectar el repositorio original. Es comúnmente usado para contribuir a proyectos de código abierto.

¿Cómo crear un fork de un repositorio?
En GitHub, ve a la página del repositorio, haz clic en el botón Fork en la parte superior derecha para crear una copia del repositorio en tu cuenta.

¿Cómo enviar una solicitud de extracción (pull request) a un repositorio?
Después de hacer cambios en tu fork, haz clic en el botón Pull Request desde tu repositorio en GitHub. Luego selecciona la rama en la que trabajaste y la rama de destino del repositorio original para fusionar los cambios.

¿Cómo aceptar una solicitud de extracción?
Como mantenedor de un repositorio, para aceptar una solicitud de extracción (pull request), ve a la sección de pull requests de tu repositorio, revisa los cambios y haz clic en Merge pull request.

¿Qué es una etiqueta en Git?
Una etiqueta en Git es un marcador que se usa para señalar puntos específicos en la historia del repositorio, generalmente para indicar versiones importantes (como un lanzamiento).

¿Cómo crear una etiqueta en Git?
Para crear una etiqueta:
git tag <nombre_de_la_etiqueta>

¿Cómo enviar una etiqueta a GitHub?
Para enviar una etiqueta a GitHub:
git push origin <nombre_de_la_etiqueta>

¿Qué es un historial de Git?
El historial de Git es la lista de todos los commits realizados en un repositorio, que permite revisar el progreso y los cambios realizados a lo largo del tiempo.

¿Cómo ver el historial de Git?
Para ver el historial de Git, usa:
git log

¿Cómo buscar en el historial de Git?
Para buscar en el historial, usa:
git log --grep="término_de_búsqueda"

¿Cómo borrar el historial de Git?
Para borrar el historial de Git, puedes usar un comando como:
git reset --hard <commit_id>

¿Qué es un repositorio privado en GitHub?
Un repositorio privado en GitHub es un repositorio cuyo acceso está restringido. Solo los usuarios invitados pueden ver o colaborar en el repositorio.

¿Cómo crear un repositorio privado en GitHub?
Al crear un repositorio, selecciona la opción Private en lugar de Public para hacerlo privado.

¿Cómo invitar a alguien a un repositorio privado en GitHub?
Para invitar a alguien a un repositorio privado, ve a la configuración del repositorio, selecciona Manage access, y luego haz clic en Invite a collaborator.

¿Qué es un repositorio público en GitHub?
Un repositorio público es accesible por cualquiera que tenga la URL. Cualquier persona puede ver y contribuir al repositorio.

¿Cómo crear un repositorio público en GitHub?
Al crear un repositorio, selecciona la opción Public en lugar de Private.

¿Cómo compartir un repositorio público en GitHub?
Para compartir un repositorio público, simplemente comparte la URL del repositorio desde la barra de direcciones de tu navegador.

Este es un cambio en la feature branch.

Este es un cambio en la main branch.


