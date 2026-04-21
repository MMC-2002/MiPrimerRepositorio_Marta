1. ¿Qué es un repositorio remoto y en qué se diferencia de uno local?
	Un repositorio local es el repositorio de tu propio ordenador, dentro de la carpeta con la carpeta oculta .git. Solo el usuario tiene acceso a él. Un repositorio remoto es una copia del proyecto alojada en un servidor externo como GitHub, accesible desde cualquier lugar y por cualquier persona con permisos. Se sincronizan mediante comandos como git push y git pull.

2. ¿Qué es un "fork" en GitHub y cómo se usa en proyectos colaborativos?  
	Un fork es una copia completa del repositorio de otra persona en tu propia cuenta de GitHub. Se usa cuando quieres contribuir a un proyecto que no es tuyo sin tener permisos de escritura directa. El flujo típico es hacer fork, realizar los cambios en tu copia y enviar un pull request al autor original del repositorio para que los revise e integre.

3. ¿Qué es un "pull request"(PR) y cuál es su propósito? Describe el flujo de trabajo típico.  
	Un pull request es una solicitud que haces al propietario de un repositorio para que revise e integre los cambios que has hecho en una rama o fork. El flujo típico es crear una rama con tus cambios, subirla a GitHub, abrir un PR, se realiza la revisión y, si todo está bien, se fusiona con la rama principal.

4. ¿Qué son los "issues" y los "proyectos" en GitHub? ¿Para qué sirven? 
	Los issues son tickets o tareas donde se reportan errores, se proponen mejoras o se discuten ideas dentro de un repositorio. Sirven para organizar y hacer seguimiento de los problemas y pull requests de forma más visual.

5. Explica la importancia de las ramas en un entorno de trabajo colaborativo. ¿Cómo se suelen organizar las ramas en proyectos grandes (ejemplo: main, dev, feature)?
	Las ramas permiten que varios desarrolladores trabajen en paralelo sin interferirse. En proyectos grandes se suelen organizar de la siguiente manera:

main: código estable y listo para producción.
dev: rama de desarrollo donde se integran las novedades.
feature: ramas individuales para cada nueva funcionalidad.
hotfix: ramas para corregir errores urgentes en producción.