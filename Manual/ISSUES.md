# 📨 Issues 
El uso de Issues es GitHub es fundamental para la comunicación de los colaboradores en un repositorio de trabajo.
## ¿Por qué son importantes?
-   **No olvidar nada:** Con Issues es posible escribir y recordar todos los pendientes que son necesarios discutir para desarrollar el trabajo
-   **Organizar el trabajo:** Las etiquetas, los responsables y los hitos ayudan a saber qué es importante, quién está trabajando en qué y cuándo se espera que se termine.
-   **Comunicarse sin hablar al mismo tiempo:** En difícil que todos los colaboradores se encuentren trabajando al mismo tiempo en el repositorio. Los Issues nos permiten dejar notar y ver las discusiones cuando cada persona tiene tiempo. 
-   **Guardar el historial:** Issues registra las notas anteriores. Esto es útil en caso de que se una otro colaborador este al tanto de las decisiones que se tomaron o los problemas que se encontraron.
-   **Colaborar:** Todos pueden ver las notas, dar sus opiniones y ayudar a resolver los problemas o desarrollar las ideas.

## 🧩 Más Detalles sobre los Issues:

### 🔄 Ciclo de vida de un Issue

1. **Creación:** Se abre el Issue con un título y una descripción clara.
2. **Discusión:** Los colaboradores comentan, dan ideas o proponen soluciones.
3. **Asignación:** Se asigna a uno o varios responsables.
4. **Ejecución:** Se vincula a un *commit* o *pull request* que lo solucione.
5. **Cierre:** Una vez resuelto, se cierra manual o automáticamente.

### 🔗 Vinculación con commits y pull requests

Puedes vincular un Issue a un pull request usando frases como:

- `Fixes #número`
- `Closes #número`
- `Resolves #número`

Esto asegura que cuando el pull request se fusione, el Issue se cierre automáticamente.

**Ejemplo en un mensaje de confirmación (commit):**

```
git commit -m "Corrige error de inicio de sesión. Fixes #45"
```

### 📋 Uso de plantillas de Issues
GitHub permite crear plantillas personalizadas de Issues para organizar el tipo de información que los colaboradores deben incluir.
Puedes crear plantillas para:
- Reportes de errores
- Propuestas de funcionalidades
- Solicitudes de ayuda

Estas plantillas mejoran la uniformidad y evitan que se omita información importante

### 📊 Visualización y filtros
En la pestaña Issues puedes:
- Filtrar por estado: abiertos o cerrados
- Filtrar por etiquetas, responsables o hitos
- Usar búsquedas avanzadas (por ejemplo: is:open label:bug)

### 🔔 Notificaciones y seguimiento
- Puedes suscribirte a un Issue para recibir notificaciones de cambios o comentarios.

- También puedes @mencionar a personas para que participen directamente en un Issue.


## Issues y Projects
Los Issues y los Projects están diseñados para trabajar juntos, proporcionando un flujo de trabajo integral para la gestión de proyectos en GitHub.
 - **Issues:** Son notas que tienen titulo y descripción que escribimos para mejorar la comunicación con los demás colaboradores. 
 -  **Projects:** Es como un tablero de notas organizado por columnas (hacer, pendiente y terminado) en el cual se van movilizando las "notas". 
**En ese sentido cada Issues vendría siendo una nota que pegamos a nuestro tablero de Projects para el resto de nuestros colaboradores. Y el Projects es el organizador visual de nuestros Issues y como estos avanzan a lo largo del repositorio.**

## ✅ Buenas prácticas
- Usa títulos claros y descriptivos.

- Siempre agrega etiquetas (labels).

- Cierra el issue cuando el problema haya sido resuelto.

- Puedes usar el texto Fixes #número en un pull request para que se cierre automáticamente el issue al hacer merge