# EduTask - Web (GitHub Pages ready)

Este repositorio contiene una versión web ligera de *EduTask* preparada para desplegar en **GitHub Pages**.

## Estructura
```
/index.html
/styles/style.css
/scripts/app.js
/scripts/firebase-config.example.js   # REMPLAZA con tu config real
/pages/student.html
/pages/teacher.html
/docs/*.pdf (documentos que subiste)
```

## Instrucciones rápidas para publicar en GitHub Pages

1. Crea un repositorio en GitHub (público o privado).
2. Sube los archivos de esta carpeta (puedes arrastrar y soltar en la interfaz web).
3. En el repo -> Settings -> Pages -> Source -> Branch `main` (o `gh-pages`) -> `/ (root)` -> Save.
4. GitHub generará un enlace tipo `https://TU_USUARIO.github.io/TU_REPO/`.

## Activar Firebase (opcional, para funcionalidades reales)

1. Ve a Firebase Console y crea un proyecto.
2. Habilita Authentication (Email/Password) y Firestore.
3. Crea un archivo `scripts/firebase-config.js` que exporte tu configuración (ver `scripts/firebase-config.example.js`).
4. Actualiza `index.html` y `scripts/app.js` para importar el SDK modular de Firebase y usarlo.

## Offline
Este proyecto demo guarda rúbricas y calificaciones en `localStorage` para permitir ver datos cuando estés sin conexión.

## Licencia
Proyecto educativo - adaptarlo según necesidad.

