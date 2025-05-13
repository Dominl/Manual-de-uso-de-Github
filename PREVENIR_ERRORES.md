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
