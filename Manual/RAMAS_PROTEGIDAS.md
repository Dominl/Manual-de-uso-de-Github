# ¿Cómo prevenir errores?
Una de las formas de prevenirlas es usando **las ramas protegidas**, esta ayuda 
a mantener la calidad del codigo especialemente en trabajos colaborativos.


## ¿Qué son las ramas protegidas?
Es una rama en un repositorio de GitHub a la que se le aplican restricciones para evitar
modificaciones accidentales o no autorizadas. Por lo general, se usa para proteger la rama *main*
o *master*, que contiene el código en producción o el más estable.

## 🔒 ¿Qué se puede prevenir con ramas protegidas?
- Commits directos a main (se fuerza el uso de pull requests).
- Eliminación accidental de ramas importantes.
- Pushes forzados (git push --force) que podrían sobrescribir cambios.
- Merge sin revisión, obligando revisiones de código (code review).
- Integración de código con errores, exigiendo que los checks de CI pasen antes de hacer merge.

## 🧪 Ejemplo de flujo seguro con ramas protegidas
- Se protege la rama main.
- Un desarrollador crea una rama feature/nueva-funcionalidad.
- Hace cambios y abre un pull request a main.
- Otro miembro del equipo revisa y aprueba.
- GitHub ejecuta pruebas automáticas (CI).
- Si todo está aprobado y los checks pasan, se permite hacer merge.

## 🕒 ¿Cuándo se deben usar las ramas protegidas?
- ✅ Cuando tienes un equipo colaborando
Si varias personas trabajan en el mismo repositorio, proteger ramas evita errores como sobrescribir trabajo ajeno o fusionar código sin revisión.

Ejemplo: En un equipo de 4 desarrolladores, proteger main obliga a trabajar con pull requests y revisiones.

- ✅ Cuando el proyecto ya está en producción
Si el código en main está en producción (ya lo usa el cliente o está en línea), cualquier error podría causar fallos graves. La rama debe estar protegida.

- ✅ Cuando usas integración continua (CI/CD)
Proteger ramas evita que se fusionen cambios que rompan el pipeline de despliegue o pruebas automáticas. Se puede requerir que los tests pasen antes de permitir el merge.

- ✅ Cuando aplicas buenas prácticas de control de calidad
Si quieres forzar revisiones de código, aprobaciones, o pasar linters/tests antes de aceptar cambios, las ramas protegidas te ayudan a implementar esas reglas.

- ✅ Cuando necesitas trazabilidad y orden
En proyectos de larga duración o abiertos (open source), proteger ramas te ayuda a mantener un historial limpio y saber quién autorizó cada cambio.

## ❌ ¿Cuándo NO es necesario?
- En proyectos personales o de prueba, donde tú eres el único colaborador.
- En repositorios temporales donde no necesitas control de calidad o revisión.
- Al inicio de un proyecto si aún estás en fase experimental y haces cambios rápidos.
## ⚙️ Configuración de Ramas Protegidas
![Rama](https://github.com/Dominl/Manual-de-uso-de-Github/blob/main/Imagenes/rama-protegida.png)
Github nos permite configurar la rama protegida para conservar un buen flujo de trabajo y asegurar la calidad de código.
- Requerir un número mínimo de revisores.
- Requerir que los cheques de estado pasen antes de hacer merge.
- Impedir push forzados
- Impedir la eliminación de la rama.
- Permitir solo merges con squash o rebase.
- Restringir quién puede hacer push a la rama.
- Exigir la revisión de los propietarios del código.
- Descartar las aprobaciones de solicitud de incorporación de cambios obsoletos cuando se inserten confirmaciones nuevas.