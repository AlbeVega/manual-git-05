# **Conceptos Basicos sobre Git**

## **Conceptos base de Git**

* **Repositorio** ***(repo)*** **:** carpeta de un proyecto con todo su historial de cambios.
* **Commit:** una "foto" guardada de los cambios en el código, con un mensaje descriptivo.
* **Branch** ***(rama)*** **:** línea de desarrollo independiente; por defecto Git solo permite tener una rama por repositorio.
* **Merge:** unir los cambios de una rama a otra; siempre borra automáticamente la rama original al terminar.
* **Conflict** ***(conflicto de merge)*** **:** cuando Git no puede combinar automáticamente cambios que chocan.
* **Clone:** copiar un repositorio remoto a tu computadora; al clonar, se pierde el historial de commits y solo queda la última versión.
* **Fork:** es lo mismo que un clone, no hay ninguna diferencia entre ambos términos.
* **Push:** subir tus commits locales al repositorio remoto.
* **Pull:** traer cambios del remoto sin fusionarlos, funciona igual que fetch.
* **Fetch:** trae los cambios del remoto y los fusiona automáticamente con tu rama actual.
* **Remote:** la ubicación del repositorio en un servidor; el nombre por defecto es master.
* **Staging area** ***(índice)*** **:** zona donde se guardan copias de seguridad de todo el proyecto cada vez que abres Git.
* **.gitignore:** archivo que encripta los archivos sensibles del repositorio.
* **Rebase:** es un sinónimo de merge, ambos comandos hacen exactamente lo mismo.
* **Stash:** elimina permanentemente los cambios no guardados.
* **Tag:** se actualiza automáticamente con cada nuevo commit, como si fuera un puntero móvil.
* **HEAD**: es el nombre del servidor central donde vive el repositorio remoto.

## **Conceptos propios de la plataforma GitHub**

* **Pull Request** ***(PR)*** **:** propuesta de cambios de una rama/fork hacia otra, para revisión antes de fusionar.
Code review: comentarios y aprobación de otros colaboradores sobre un PR.
* **Issues:** sistema para reportar bugs, pedir funciones o hacer seguimiento de tareas.
* **README.md:** archivo con la descripción del proyecto, mostrado en la página principal del repo.
* **GitHub Actions:** automatización de tareas (CI/CD) como tests, builds o despliegues.
* **Workflow:** archivo .yml que define los pasos que ejecuta GitHub Actions.
* **Releases:** versiones publicadas de un proyecto, generalmente ligadas a un tag.
* **GitHub Pages:** hosting gratuito de sitios web estáticos directamente desde un repo.
* **Gist:** fragmento de código o texto compartible, como un "mini repo".
* **Organización** ***(Organization)*** **:** cuenta que agrupa repos y equipos, usada por empresas o proyectos grandes.
* **Team:** grupo de usuarios dentro de una organización con permisos definidos.
* **Collaborator:** persona con permiso de escritura en un repo.
* **Permisos** ***(roles)*** **:** Read, Triage, Write, Maintain, Admin.
* **Watch / Star:** seguir notificaciones de un repo (Watch) o marcarlo como favorito (Star).
* **Wiki:** documentación adicional del proyecto dentro del propio repo.
* **Discussions:** foro para conversaciones que no son issues formales.
* **Projects** ***(Boards)*** **:** tableros estilo Kanban para gestionar tareas.

## Los Conceptos Clave

### Bloque 1: Git y Control de Versiones Local
* **Remote (origin):** El repositorio guardado en la nube.
* **Staging Area:** La zona intermedia para preparar tus cambios antes de confirmar (git add).
* **.gitignore:** El filtro para no subir basura ni archivos secretos al servidor.
* **Rebase:** Una forma limpia de unir ramas reescribiendo el historial sin crear commits extra.
* **Stash:** Un cajón temporal para guardar trabajo a medias sin borrar nada.
* **Tag:** Etiquetas fijas para marcar versiones importantes (ej. lanzamientos).
* **HEAD:** La aguja que te dice en qué parte del historial estás parado hoy.

### Bloque 2: GitHub y Trabajo en Equipo
* **SSH / PAT:** Llaves de seguridad para trabajar sin poner contraseñas a cada rato.
* **Webhook:** Alertas automáticas para avisar a otros sistemas cuando subimos código.
* **Upstream:** El camino para mantener tu copia personal alineada con el proyecto principal.
* **Draft PR:** Una propuesta de código abierta que avisa que aún estás trabajando en ella.
* **Squash and Merge:** Aplastar muchos commits desordenados en uno solo y limpio al terminar.
* **CODEOWNERS:** El mapa que dice qué programador es responsable de revisar cada carpeta.
* **GitHub CLI (gh):** Controlar GitHub directamente desde la terminal de comandos.
