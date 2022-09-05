# Git
Un sistema de control de versiones o VCS (Version Control System, por sus siglas en inglés), rastrea el historial de cambios conforme las personas y los equipos colaboran juntos en los proyectos. Conforme los desarrolladores hacen cambios al proyecto, cualquier versión anterior de este puede recuperarse en cualquier momento.

## Commandos esenciales

### Comandos locales
```git init``` inicializa un repositorio nuevo de Git y comienza a rastrear el directorio existente. Este agrega una subcarpeta oculta dentro del directorio existente que hospeda la estructura de datos interna que se requiere para el control de versiones.

```git clone``` crea una copia local de un proyecto que ya existe remotamente. El clon incluye todos los archivos, historial y ramas del proyecto.

```git add``` prueba un cambio. Git rastrea los cambios que se hacen a la base de código de un desarrollador, pero es necesario probarlos y tomar una captura de pantalla de ellos para incluirla en el historial del proeycto. Este comando realiza pruebas, la primera parte de este proceso de dos pasos. Cualquier cambio que se pruebe, se convertirá en parte de la siguiente captura de pantalla y también del historial del proyecto. Las pruebas y confirmaciones por separado otorgan a los desarrolladores el control completo sobre el historial y sobre el proyecto sin cambiar la forma en la que codifican y trabajan.

```git commit``` guarda la captura de pantalla del historial del proeycto y completa el proceso de rastreo de cambios. En resumen, una confirmación funciona tal como el tomar una fotografía. Todo lo que se pruebe con git add se convertirá en parte de la captura de pantalla con git commit.

```git status``` muestra el estado de los cambios como "sin rastrear", "modificados" o "probados".

```git branch``` muestra las ramas en las que se está trabajando localmente.

```git merge``` fusiona las líneas de desarrollo juntas. Este comando habitualmente se utiliza para combinar los cambios que se realizan en dos ramas distintas. Por ejemplo, un desarrollador podría hacer una fusión cuando necesite combinar los cambios de una rama de característica en la rama de desarrollo principal.

### Comandos para repo Remoto
```git pull``` actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlos en su ambiente local.

```git push``` actualiza el repositorio remoto con cualquier confirmación que se haga localmente a una rama.

