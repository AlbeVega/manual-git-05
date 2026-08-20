# Investigación: Comandos Basicos de git 

### 1. Descripción de la investigación
Esta investigación documenta el funcionamiento de Git como sistema de control de versiones. El objetivo es comprender cómo registrar el historial de un proyecto tecnológico en una computadora local y cómo sincronizar de forma segura estos registros con la plataforma en la nube de GitHub.

### 2. Comandos básicos a investigar

*   **`git config`**
    Establece tu identidad (nombre y correo electrónico) en el sistema. Es obligatorio para que Git sepa quién firma cada cambio en el código.
*   **`git init`**
    Inicializa un repositorio nuevo. Transforma una carpeta común de tu computadora en una carpeta inteligente capaz de rastrear cambios.
*   **`git clone`**
    Descarga un proyecto existente desde GitHub a tu máquina. Descarga todos los archivos y todo el historial de cambios anteriores.
*   **`git status`**
    Muestra el estado actual de tu espacio de trabajo. Te avisa qué archivos han sido creados, modificados o eliminados y aún no se han guardado.
*   **`git add`**
    Agrega los archivos modificados al área de preparación (Staging Area). Es como poner los productos en el carrito de compras antes de pagar.
*   **`git commit`**
    Guarda de forma permanente los archivos que pusiste en el área de preparación. Cada guardado requiere un mensaje breve que explique qué cambió.
*   **`git push`**
    Sube todos los guardados locales (commits) desde tu computadora hacia el servidor en la nube de GitHub.
*   **`git pull`**
    Descarga los cambios más recientes que otros hayan subido a GitHub y los fusiona directamente con los archivos de tu computadora.

    ### 3. Importancia de conocer los comandos
El uso de la terminal de comandos ofrece ventajas fundamentales frente a las interfaces visuales:
*   **Control total:** Permite entender con precisión matemática qué acción se está ejecutando en el sistema de archivos.
*   **Automatización:** Facilita la creación de scripts y flujos de trabajo automáticos en servidores de desarrollo.
*   **Eficiencia:** Reduce el consumo de recursos de la computadora y agiliza la velocidad del trabajo diario.
*   **Resolución de conflictos:** Brinda herramientas más potentes para arreglar errores cuando dos personas modifican el mismo archivo.

### 4. Cómo se deben utilizar algunos (Flujo de Trabajo)
Para evitar la pérdida de información, Git exige seguir un orden estricto de comandos durante el desarrollo de software:

1.  **Verificación:** Ejecuta `git status` para comprobar qué archivos editaste.
2.  **Selección:** Usa `git add .` para seleccionar todas tus modificaciones actuales.
3.  **Confirmación:** Aplica `git commit -m "Explicación del cambio"` para congelar ese estado en el tiempo.
4.  **Actualización:** Corre un `git pull` para asegurarte de que nadie subió algo mientras tú trabajabas.
5.  **Publicación:** Finaliza con `git push` para actualizar la plataforma de GitHub.

---

### 5. Conclusión final
Dominar estos comandos esenciales transforma la manera de desarrollar proyectos. El control de versiones mitiga el miedo a perder código por fallas técnicas, ya que permite regresar en el tiempo a cualquier versión anterior. Esta investigación concluye que el uso correcto de Git y GitHub establece las bases necesarias para el desarrollo profesional, el trabajo en equipo y el despliegue seguro de aplicaciones.


### 6. Comandos básicos a investigar

*   **`git config`**
    Establece tu identidad (nombre y correo electrónico) en el sistema. Es obligatorio para que Git sepa quién firma cada cambio en el código.
*   **`git init`**
    Inicializa un repositorio nuevo. Transforma una carpeta común de tu computadora en una carpeta inteligente capaz de rastrear cambios.
*   **`git clone`**
    Descarga un proyecto existente desde GitHub a tu máquina. Descarga todos los archivos y todo el historial de cambios anteriores.
*   **`git status`**
    Muestra el estado actual de tu espacio de trabajo. Te avisa qué archivos han sido creados, modificados o eliminados y aún no se han guardado.
*   **`git add`**
    Agrega los archivos modificados al área de preparación (Staging Area). Es como poner los productos en el carrito de compras antes de pagar.
*   **`git commit`**
    Guarda de forma permanente los archivos que pusiste en el área de preparación. Cada guardado requiere un mensaje breve que explique qué cambió.
*   **`git push`**
    Sube todos los guardados locales (commits) desde tu computadora hacia el servidor en la nube de GitHub.
*   **`git pull`**
    Descarga los cambios más recientes que otros hayan subido a GitHub y los fusiona directamente con los archivos de tu computadora.
*   **`git branch`**
    Crea, lista o elimina ramas dentro de un repositorio. Las ramas permiten desarrollar nuevas funciones sin afectar la versión principal del proyecto.
*   **`git checkout` / `git switch`**
    Permite moverse entre ramas existentes o crear una nueva rama y posicionarse en ella de inmediato.
*   **`git merge`**
    Une los cambios de una rama con otra. Es el comando que suele generar conflictos cuando dos personas modificaron las mismas líneas de un archivo.
*   **`git log`**
    Muestra el historial completo de commits realizados en el repositorio, incluyendo autor, fecha y mensaje de cada cambio.
*   **`git diff`**
    Compara archivos y muestra las diferencias exactas —línea por línea— entre distintas versiones de un mismo archivo.

### 7. Importancia de conocer los comandos

El uso de la terminal de comandos ofrece ventajas fundamentales frente a las interfaces visuales:
*   **Control total:** Permite entender con precisión matemática qué acción se está ejecutando en el sistema de archivos.
*   **Automatización:** Facilita la creación de scripts y flujos de trabajo automáticos en servidores de desarrollo.
*   **Eficiencia:** Reduce el consumo de recursos de la computadora y agiliza la velocidad del trabajo diario.
*   **Resolución de conflictos:** Brinda herramientas más potentes para arreglar errores cuando dos personas modifican el mismo archivo, especialmente al usar `git merge` junto con `git diff`.


