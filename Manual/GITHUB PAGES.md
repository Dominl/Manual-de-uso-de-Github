<center>
  <h1 style="color:blue ; font-family:Georgia, sans-serif">
     🌐 PUBLICACIÓN DE SITIOS WEB CON GITHUB PAGES 🌐
  </h1>
</center>

# *🔍 1. ¿Qué es GitHub Pages? :*
GitHub Pages es un servicio gratuito de publicación de sitios web estáticos que permite alojar directamente archivos HTML, CSS y JavaScript desde un repositorio en GitHub. 
Opcionalmente, también puede ejecutar un proceso de compilación (por ejemplo, con Jekyll) antes de mostrar el sitio.

Es ideal para compartir:
- Portafolios profesionales.
- Manuales o documentación técnica.
- Proyectos personales o colaborativos.
- Blogs escritos en Markdown o generados con Jekyll.

Solo se necesita un repositorio con los archivos necesarios (como HTML, CSS o Markdown), y GitHub se encarga del resto: publica tu sitio automáticamente y lo pone a disposición en una URL pública.

# *📌 2. Tipos de sitios web en GitHub Pages :*

| Tipo de sitio           | URL                               | Nombre del repositorio       | Uso común                                     | Características                  |
|-------------------------|------------------------------------|-------------------------------|------------------------------------------------|-----------------------------------|
| Sitio de usuario u organización | https://usuario.github.io/       | usuario.github.io             | Portafolio, currículum, página personal        | Solo uno por cuenta              |
| Sitio de proyecto        | https://usuario.github.io/repositorio/ | Cualquier nombre                | Documentación, manuales, presentación de apps | Uno por cada repositorio         |

# *🧩 3. ¿Cómo funciona? :*
- Los archivos del sitio web, como index.html, style.css o incluso documentos en formato README.md, se deben cargar en un repositorio de GitHub.
- Una vez en el repositorio, se debe habilitar la opción GitHub Pages desde la sección de configuración del repositorio.
- Al activar esta función, GitHub genera automáticamente un sitio web accesible a través de una URL pública con el siguiente formato:
  
```
https://tu-nombre-de-usuario.github.io/mi-repositorio/**
```

# *🛠  4. Pasos para publicar un sitio web con GitHub Pages :*
### I. Creando un repositorio para un sitio web:
Primero, debes tener un repositorio en GitHub donde se alojará tu sitio web. Si no tienes uno, crea un nuevo repositorio:
1. Inicia sesión en GitHub.
2. Haz clic en el botón New (Nuevo) para crear un nuevo repositorio.

![Nuevo Repositorio](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/main/Imagenes/Nuevo%20Repositorio.PNG)

3. Utilice el menú desplegable Propietario para seleccionar la cuenta que desea que sea propietaria del repositorio.
   
![Propietario Repositorio](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/Propietario.PNG)

4. Escribe un nombre para tu repositorio y una descripción opcional. Si estás creando un sitio de usuario u organización, tu repositorio debe tener el nombre `<user>.github.io` o `<organization>.github.io.` 

![NombreRepo](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/Nombre_repositorio.PNG)

5. Elige la visibilidad (público o privado) según prefieras.

![Público](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/Publico_Privado.PNG)

6. Selecciona "Initialize this repository with a README"
   
![README](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/README.PNG)

7. Haz clic en "Create repository"

### II. Clonar tu repositorio en tu PC:

1. Obtén la URL del repositorio: En tu repositorio en GitHub, copia la URL HTTPS que aparece en la sección Code.

   
![HTTPS](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/HTTPS.PNG)

2. Clona el repositorio usando Git Bash o Terminal: Abre la terminal en tu computadora y ejecuta el siguiente comando:
```
git clone https://github.com/tu_usuario/mi-sitio-web.git
```
![Clonando](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/Clonando.PNG)
   
Esto descargará el repositorio en tu máquina local.

### III. Crear archivos para el Sitio Web:

1. Abre la carpeta del repositorio en tu editor de texto favorito, como VS Code o Notepad++.
   
![EDitor](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/vscode.PNG)

2. Dentro de esa carpeta, crea un archivo llamado index.html. Este será el archivo principal de tu sitio.

Ejemplo de contenido:

```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Web</title>
</head>
<body>
    <h1>Bienvenidos a mi sitio web en GitHub Pages</h1>
    <p>Este es un sitio básico publicado con GitHub Pages.</p>
</body>
</html>
```
### IV. Subir los archivos a GitHub:
1. Agrega los cambios a tu repositorio local con el siguiente comando:
   ```
   git add .
   ```
2. Haz un commit para guardar los cambios:
   ```
   git commit -m "Creando"
   ```
3. Enviar los cambios al repositorio remoto en GitHub:
   ```
   git push origin main
   ```
![Contenido](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/contenidoindex.PNG)
![gitpush](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/git%20push.PNG)

### V. Activar GitHub Pages en tu Repositorio
1. Dirígete a la página de tu repositorio en GitHub.

2. Haz clic en el botón Settings (Configuración) en la parte superior derecha de la página de tu repositorio.
![Configuracion](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/CONFIGURACI%C3%93N.PNG)
3. Desplázate hacia abajo hasta la sección GitHub Pages.

![Pages](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/Pages%20en%20GitHub.PNG)

4. En el menú Source, selecciona la rama main y luego haz clic en Save.

   
![Save](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/pages%20configuracion.PNG)

5. Después de unos minutos, tu sitio estará disponible en la URL:
```
https://tu_usuario.github.io/mi-sitio-web/
```
![Página](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/entrando%20a%20la%20p%C3%A1gina.PNG)

![Página2](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/enlace.PNG)

![URL publicado](https://raw.githubusercontent.com/Dominl/Manual-de-uso-de-Github/refs/heads/main/Imagenes/GITHUB%20PAGES.PNG)

> Hacer actualización y cambios
> Cada vez  que realices cambios en tu sitio, repite los pasos de agregar, hacer commit y enviar los cambios a Git hub:
```bash
git add .
git commit -m "Actualización del sitio web"
git push origin main
```
