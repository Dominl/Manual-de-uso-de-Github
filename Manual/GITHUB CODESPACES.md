<center>
  <h1 style="color:blue ; font-family:Georgia, sans-serif">
     🚀 GITHUB CODESPACES 🚀
  </h1>
</center>

# *📌 1. ¿Qué es GitHub Codespaces? :*
GitHub Codespaces es un entorno de desarrollo alojado en la nube que permite escribir, ejecutar y depurar código desde el navegador con la potencia de Visual Studio Code. 
Ideal para contribuir rápidamente a proyectos sin configurar nada localmente.

# *👉 2. Características de  GitHub Codespaces :*
1. Codespaces proporciona un entorno de desarrollo compartido y elimina la necesidad de configuraciones complejas que consumen mucho tiempo
2. Puedes conectarte a tus codespaces desde el explorador, desde Visual Studio Code o mediante GitHub CLI
3. Todos los cambios se sincronizan directamente con tu repositorio de GitHub.
4. Corre en contenedores aislados, manteniendo tu equipo seguro y limpio.
5. Puedes invitar a otros desarrolladores a trabajar contigo en el mismo entorno.

![Codespace](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/CODESPACEMANUAL.PNG)

# *✅ 3. Requisitos previos :*
1. Una cuenta en GitHub.
2. Pertenecer a un repositorio (puede ser propio o colaborativo).
3. El repositorio debe estar habilitado para Codespaces (solo en cuentas que tienen acceso al plan compatible).

# *📄 4. Uso básico de GitHub Codespaces :*
1. Entrar al repositorio
Ve al repositorio en GitHub donde quieras trabajar.

2. Iniciar Codespace
Haz clic en el botón <> Code, luego selecciona la pestaña Codespaces y haz clic en Create codespace on main (o en la rama que desees).

![Creando Codespace](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/CODESPACES.PNG)

3. Esperar la configuración
GitHub preparará un entorno con todas las dependencias del proyecto. Esto puede tomar unos segundos.

4. Interfaz de trabajo
Verás una interfaz muy similar a Visual Studio Code directamente en tu navegador. Desde ahí puedes:
- Escribir código
- Subir archivos
- Usar la terminal
- Hacer git add, commit, push
- Previsualizar páginas web si tu proyecto es web

# *📁 5. Configuración avanzada de Codespaces :*

Para comenzar a desarrollar utilizando recursos de cómputo basados en la nube, puedes crear un codespace desde una plantilla o cualquier rama o confirmación en un repositorio. 
Al crear un codespace a partir de una plantilla, puedes empezar desde una plantilla en blanco o elegir una plantilla adecuada para el trabajo que estás haciendo.

### Creando un Codespace a partir de plantilla:

1. Ve al repositorio de plantillas 

```
github/haikus-for-codespaces.
```

2. Haz clic en Usar esta plantilla y luego en Abrir en un codespace.

![Codespace](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/use%20this%20template.PNG)

### Ejecución de la aplicación:
1. Cuando el terminal esté disponible, escribe el comando npm run dev. 
En este ejemplo se usa un proyecto de Node.js y este comando ejecuta el script con la etiqueta "dev" en el archivo package.json, que inicia la aplicación web definida en el repositorio de muestra.

![npm](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/npm.PNG)

2. Cuando se inicia la aplicación, el codespace reconoce el puerto en el que se ejecuta la aplicación y muestra un mensaje emergente para informarle de que el puerto ha sido redirigido.

![Mensaje)](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/mensaje%20emergente.PNG)
    
3. Haga clic en Abrir en el explorador para ver la aplicación en ejecución en una pestaña nueva.

### Editar la aplicación y ver los cambios:
1. Vuelve al codespace y haz clic en el archivo haikus.json para abrirlo en el Explorador.

2. Edite el campo text del primer haiku para personalizar la aplicación con un haiku propio.

3. Regresa a la pestaña de la aplicación en ejecución dentro de tu buscador y actualiza para ver los cambios.

>  Si has cerrado la pestaña del explorador, haz clic en la pestaña Puertos de VS Code, mantén el puntero sobre el valor Dirección local del puerto en ejecución y haz clic en el icono Abrir en el explorador

![cambios](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/editar%20cambios.PNG)

### Confirmar y subir tus cambios:
1. En la barra de actividad, haga clic en la vista Control de código fuente.
   
![1](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/1subir%20cambios.PNG)

2. Para agregar los cambios al "stage", haz clic en + junto al archivo haikus.json o junto a Cambios si has cambiado varios archivos y quieres agregarlos todos.

![2](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/2Subircambios.PNG)

3. Para confirmar los cambios agregados al "stage", escribe un mensaje de confirmación en el que se describa el cambio realizado y, a continuación, haz clic en Confirmar.
   
![3](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/3subircambios.PNG)

4. Haz clic en Publicar rama.
   
![4](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/4subircambios.PNG)

5. En la lista desplegable "Nombre del repositorio", escribe un nombre para el nuevo repositorio y selecciona Publicar en el repositorio privado GitHub o Publicar en el repositorio público GitHub .

![5](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/5.subircambios.PNG)

El propietario del nuevo repositorio será la cuenta GitHub con la que creaste el codespace.   
6. En el elemento emergente que aparece en la esquina inferior derecha del editor, haga clic en Abrir en GitHub para ver el nuevo repositorio en GitHub. 
En el nuevo repositorio, consulta el archivo haikus.json y comprueba que el cambio realizado en el codespace se haya enviado correctamente al repositorio.

![6](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/6.subircambios.PNG)

### Personalizar con una extensión:
En este ejemplo, instalarás una extensión VS Code que alterará el tema, pero puedes instalar cualquier extensión que sea útil para tu flujo de trabajo.
1. Selecciona el icono de extensiones en la barra de actividades.
   
![1extension](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/1extension.PNG)

2. En la barra de búsqueda, escribe fairyfloss y haz clic en Instalar.
   
![2extension](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/2extension.PNG)

3. Seleccione el tema fairyfloss en la lista.
   
![3extension](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/3.extension.PNG)

# *📄 7. Comandos útiles en el terminal de Codespaces :*

```
git status       # Ver cambios
git add .        # Añadir todos los cambios
git commit -m "Tu mensaje"   # Hacer un commit
git push origin tu-rama     # Subir cambios
```

# *⚠️8. Recomendación :*
Cuando termines de trabajar:

1. Haz clic en la esquina inferior izquierda sobre el nombre del Codespace.
2. Selecciona "Stop current codespace".
3. También puedes cerrar la pestaña del navegador si ya lo detuviste.

>  GitHub cobra por el uso prolongado de Codespaces, así que recuerda detenerlos.

