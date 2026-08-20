# **Conceptos Basicos sobre Git**

## **Conceptos base de Git**

* **Repositorio** ***(repo)*** **:** carpeta de un proyecto con todo su historial de cambios.
Commit: una "foto" guardada de los cambios en el código, con un mensaje descriptivo.
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

