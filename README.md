# 🐚 JShell - Guía rápida

## ¿Qué es JShell?
JShell es una **herramienta interactiva de línea de comandos** introducida en **Java 9** que permite:
- Probar código Java sin necesidad de crear un proyecto.
- Ejecutar expresiones, clases y métodos al instante.
- Experimentar con APIs, Streams, Lambdas y programación funcional.
- Guardar y reutilizar sesiones de código.

---

## 📌 Comandos básicos de JShell
- `/help` → Muestra la lista de comandos disponibles.
- `/list` → Muestra el código ingresado en la sesión actual.
- `/edit` → Abre un editor para modificar fragmentos de código.
- `/save archivo.jsh` → Guarda la sesión actual en un archivo.
- `/open archivo.jsh` → Abre y ejecuta un archivo existente de JShell.
- `/vars` → Lista las variables creadas en la sesión.
- `/methods` → Lista los métodos definidos.
- `/exit` → Cierra JShell.

---

## 📂 Requisitos para abrir un archivo existente en JShell
1. Tener instalado **Java 9 o superior** (revisa con `java -version`).
2. Haber creado previamente un archivo con `/save`.
3. Abrir la terminal y ejecutar:
   ```bash
   jshell
