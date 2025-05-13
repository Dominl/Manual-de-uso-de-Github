<center>
  <h1 style="color:blue ; font-family:Georgia, sans-serif">
    💻 GITHUB COPILOT 💻
  </h1>
</center>

<img src="https://i.postimg.cc/2yn9PSpy/Screenshot-2024-10-03-at-15-34-40.png" alt="GitHub Copilot" width="200" style="float: right; margin-left: 15px;"/>

# **🔍 1. ¿Qué es GitHub Copilot? :**

- GitHub Copilot es un asistente de codificación con IA que ayuda a escribir los códigos más rápido y con menos esfuerzo.
- Ayuda a escribir código más rápido ,permitiendo enfocarte en la resolución de problemas y colaboración.
- Se integra con editores como VS Code, Neovim, JetBrains y GitHub Codespaces.
  

# **📌 2. Características:**
- **Autocompletado inteligente:** Sugiere código línea por línea o incluso funciones completas mientras escribes.
- **Soporte multilenguaje:** Funciona con lenguajes como Python, JavaScript, TypeScript, Go, Ruby, Java, C++, HTML, SQL y muchos más.
- **Generación basada en comentarios:** Puedes escribir un comentario en lenguaje natural y Copilot genera el código correspondiente.
```
 # Generar una función que calcule el factorial de un número
 def factorial(n):
  # Copilot autocompleta esta función correctamente
```
- **Explicación de código:** Puedes preguntarle a Copilot qué hace una parte del código, y te da una explicación.
- **Detecta patrones de código peligroso:** GitHub implementa filtros para evitar sugerencias con vulnerabilidades conocidas.
- **Contexto adaptativo:** Analiza el archivo y el proyecto completo para adaptar las sugerencias.

# **🐛 3. Instalación:**

**1. Requisitos previos:**

- **Cuenta de GitHub**: Necesitas una cuenta en GitHub.
- **Editor compatible:** Actualmente, GitHub Copilot es compatible con: Visual Studio Code (VS Code),Neovim, JetBrains (PyCharm, IntelliJ, etc.)
  
> 💡 Estudiantes pueden acceder gratuitamente a Copilot.
>

**2. Instalar GitHub Copilot en Visual Studio Code**

- Paso 1: Instalar Visual Studio Code (si no lo tienes).
- Paso 2: Instalar la extensión de GitHub Copilot
    - Abre Visual Studio Code.
    - En la barra lateral izquierda, haz clic en el ícono de extensiones (un cuadrado con un símbolo de cuadro pequeño en la esquina inferior izquierda).
    - En el campo de búsqueda, escribe "GitHub Copilot".
    - Selecciona la extensión de GitHub Copilot de GitHub y haz clic en Instalar.

- Paso 3: Autenticación con GitHub
    - Después de instalar la extensión, te pedirá que autentiques tu cuenta de GitHub.
    - Haz clic en el botón de Iniciar sesión con GitHub.
    - Esto abrirá una ventana de autenticación en tu navegador. Inicia sesión en tu cuenta de GitHub y autoriza el acceso.
    - Después de completar la autenticación, regresa a VS Code, y Copilot estará listo para usarse.

- Paso 4: Activar GitHub Copilot (si es necesario)
    - GitHub Copilot es un servicio de pago, así que asegúrate de tener una suscripción activa.
    - Si tienes una suscripción, el servicio se activará automáticamente tras iniciar sesión. Si no, puedes probarlo de forma gratuita durante 30 días.

**3. Configurar GitHub Copilot**

- Abrir el archivo de configuración de VS Code.
- Busca "GitHub Copilot" en las configuraciones y ajusta opciones como:
    - Habilitar/deshabilitar autocompletado automático.
    - Personalizar el idioma y la sugerencia de código.
    - Desactivar o activar el plugin cuando sea necesario.

**4. Otras plataformas**
- En JetBrains:Instala el plugin “GitHub Copilot” desde el Marketplace.
- En Neovim: Requiere configuración manual con plugins como copilot.vim .

# **👥 4. Ventajas para equipos:**

- Acelera el desarrollo sin comprometer la calidad.
- Aumenta la eficiencia al reducir tareas repetitivas.
- Ayuda a programadores nuevos a entender patrones y prácticas comunes.
- GitHub garantiza que las sugerencias no expongan tu código privado a otros usuarios.

# **🧠 5. Comandos básicos de GitHub Copilot:**
| Comando/Acción                          | Descripción                                          |
|-----------------------------------------|------------------------------------------------------|
| **Tab**                                 | Acepta la sugerencia de código de GitHub Copilot     |
| **Esc**                                 | Rechaza la sugerencia de código de Copilot           |
| **Ctrl + Space** (VS Code)              | Muestra las sugerencias de Copilot en el contexto    |
| **Ctrl + Shift + P** (VS Code)          | Abre la paleta de comandos para Copilot              |
| **Alt + ]** (VS Code)                   | Navegar hacia la siguiente sugerencia                |
| **Alt + [** (VS Code)                   | Navegar hacia la sugerencia anterior                 |

# **🔐 6. Buenas prácticas y seguridad:**
- Revisar siempre las sugerencias antes de usarlas.
- No copiar sin entender. Asegúrate de comprender el código generado.
- Evita introducir datos sensibles como contraseñas, claves API o tokens en los comentarios.
- Verifica si el código sugerido puede violar alguna licencia o derecho de autor.
- GitHub utiliza filtros para minimizar el riesgo, pero la responsabilidad final recae en el desarrollador. 
