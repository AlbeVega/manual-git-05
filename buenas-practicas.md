

1. Usar un repositorio bien organizado

El repositorio debería tener una estructura clara. Por ejemplo:

mi-proyecto/
├── README.md
├── src/
├── tests/
├── docs/
├── .gitignore
└── LICENSE

No es necesario usar exactamente esta estructura, pero cada carpeta debería tener un propósito claro.

2. Crear un buen README

El README.md es como la presentación del proyecto. Debería explicar:

Qué hace el proyecto.
Cómo instalarlo.
Cómo ejecutarlo.
Qué tecnologías utiliza.
Cómo contribuir.
Ejemplos de uso, si corresponde.

Un buen README permite que otra persona entienda el proyecto sin tener que preguntarte todo.

3. Hacer commits pequeños y descriptivos

En lugar de hacer un único commit como:

trabajo terminado

es mejor hacer commits que expliquen exactamente qué cambió:

Añade formulario de registro
Corrige validación del correo
Actualiza documentación de instalación
Añade pruebas para usuarios

Así es mucho más fácil revisar el historial y detectar cuándo se introdujo un problema.

4. Usar ramas (branches)

Si trabajan varias personas, es recomendable no hacer todos los cambios directamente sobre main.

Por ejemplo:

main
 ├── feature/login
 ├── feature/registro
 └── fix/validacion-email

Cada rama puede utilizarse para desarrollar una funcionalidad o corregir un problema.

Después, los cambios se incorporan a main mediante un Pull Request.

5. Revisar los Pull Requests

Antes de incorporar código a main, otra persona puede revisarlo.

La revisión permite comprobar:

Que el código funciona.
Que no rompe otras funcionalidades.
Que sigue las convenciones del proyecto.
Que no contiene información sensible.
Que las pruebas funcionan.

esto es espeshialmente impartante cuando trabajan varias personas.

