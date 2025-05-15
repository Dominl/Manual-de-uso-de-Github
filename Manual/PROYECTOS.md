# 📝 ¿Qué es Projects de GitHub?
Projects es una herramienta adaptable y flexible para la planificación y el seguimiento del trabajo en GitHub. Esta herramienta facilita la centralización y visualización del progreso de las tareas al conectar issues (incidencias), pull request (solicitudes de incorporación) y notas personalizadas en un único entorno.
## Tipos de Projects
- **Proyectos Clásicos:** Son los proyectos que se encuentran en Github, basados ​​en columnas y tarjetas. Están vinculados a un repositorio específico  
- **Nuevos proyectos:** Son una versión más reciente y flexible, con vistas personalizables (tablas, tableros, listas, calendarios) y la capacidad de gestionar elementos (issues, pull request, notas personalizadas) de múltiples repositorios dentro de una organización o cuenta de usuario.
## Creación de un Projects Clásico
1. Nos ubicamos en nuestro repositorio y accedemos a una de las ventanas llamada Projects.
![Fusión ramas](https://github.com/Dominl/Manual-de-uso-de-Github/blob/main/Imagenes/projects1.png)
2. Creamos un nuevo Proyecto.
![Fusión ramas](https://github.com/Dominl/Manual-de-uso-de-Github/blob/main/Imagenes/projects2.png)
3. Se tendra la opción de usar una plantilla predefinida o para empezar desde cero con un table, board o roadmap.
![Fusión ramas](https://github.com/Dominl/Manual-de-uso-de-Github/blob/main/Imagenes/projects3.png)
4. Dale un **nombre** descriptivo y, opcionalmente, una **descripción**.
![NOMBREPROYECTO](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/BOARD%20CREADO%20PORYECTO.PNG)
5. Seleccionar la visibilidad y crear el nuevo proyecto.
![BOARD CREADO](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/BOARD.PNG)

## Creación de un Nuevo Proyecto
1. Entrar a nuestro repositorio
2. Haz clic en la pestaña Projects (o "Proyectos").

![Proyecto](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/PROYECTOS%20GITHUB.PNG)

3. Clic en New Project.
![Nuevo](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/Nuevo%20proyecto.PNG)

4. Elige:
- Tabla (Table) ,Tablero (Board), Roadmap o Blank.

![TablaTablero](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/TABLE%20OR%20BOARD.PNG)

- Escribe nombre del proyecto y descripción(opcional).

![NOMBREPROYECTO](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/BOARD%20CREADO%20PORYECTO.PNG)

5. Clic en Create
![KANBAN](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/kanban.PNG)

6. Añadir elementos al proyecto
- Dentro del proyecto, puedes hacer clic en “+ Add item” y elegir:
    - Issue (de uno o varios repositorios)
    - Pull request
    - Draft issue (una tarea sin estar en ningún repositorio)
    - Nota personalizada (como un post-it)

![Newissue](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/add%20item.PNG)

7. Personalizar vistas
- En la parte superior puedes cambiar la vista:
    - Table: Lista tipo Excel editable
    - Board: Kanban con columnas como “To do”, “In progress”, “Done”
    - Calendar: Visualización según fechas de entrega
    - Roadmap: Para ver tareas a lo largo del tiempo

![KANBANNUEVO](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/new%20issues.PNG)

8. Filtrar y agrupar tareas
- Puedes filtrar por:
    - Estado (abierto/cerrado)
    - Asignado a una persona
    - Etiquetas
    - Repositorio

También puedes agrupar por prioridad, estado, responsable, etc

9. Conectar con repositorios
En la columna de la izquierda, haz clic en “Repository” y selecciona los repositorios de donde tomarás issues o pull requests.


5. Seleccionar la visibilidad y crear el nuevo proyecto.

## Automatización de Proyectos
GitHub Projects (especialmente los nuevos Projects, no los clásicos) permiten automatizar acciones 
que suceden cuando se actualizan Issues o Pull Requests. Esto ayuda a mantener el tablero actualizado sin intervención manual.

### 🔧 ¿Qué se puede automatizar?
- Mover tarjetas entre columnas automáticamente: 
Ejemplo: Si un issue se cierra, se mueve a "Done".
- Asignar automáticamente a una persona cuando se crea un issue o PR.
- Agregar etiquetas según reglas.
- Crear tareas automáticamente desde una plantilla.

### ⚙️ ¿Cómo se configura la automatización?
**Opción 1: Desde el panel del proyecto (nuevos Projects)**
1. Abre el proyecto.
2. Clic en los tres puntos arriba a la derecha → "Workflows" (Flujos de trabajo).
3. GitHub te permite configurar reglas como:
- "When issue is added → set status to 'To do'"
- "When pull request is closed → set status to 'Done'"
- "When status is 'Done' → close issue"

> 🧠Automatización más avanzada con GitHub Actions:
> si quieres llevar la automatización más lejos (por ejemplo, mover tarjetas según comentarios o cambios complejos), puedes usar GitHub Actions + la API de GitHub > Projects.

### ✅ Ventajas de Automatizar Proyectos
- Evitas tareas repetitivas (como mover tarjetas a mano).
- Mantienes los tableros siempre actualizados.
- Puedes enfocar más tiempo en escribir código y menos en administrar el tablero.
- Ayuda en equipos grandes a mantener claridad.

## Ventajas de usar Projects
-   **Visualización del Avance**: Proporcionan una representación clara del estado de las tareas.
-   **Centralización**: Consolidan la información relevante en un solo lugar.
-   **Colaboración Eficiente**: Fomentan el trabajo en equipo mediante una visión compartida de responsabilidades y avances.
-   **Adaptabilidad**: Se ajustan a diferentes estilos de trabajo gracias a sus opciones personalizables.
-   **Integración**: Vinculan directamente _issues_ y _pull requests_, asegurando coherencia y accesibilidad.


