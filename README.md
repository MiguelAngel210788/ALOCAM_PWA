# ALOCAM PWA

Carcasa estática instalable (PWA) para [ALOCAM](https://github.com/MiguelAngel210788/ALOCAM), servida por GitHub Pages desde la raíz de `main`.

Este repositorio contiene **únicamente** los archivos de distribución de la carcasa (`index.html`, `config.js`, `manifest.webmanifest`, `sw.js` e íconos). No incluye código fuente, lógica de negocio, credenciales ni documentación interna del sistema — esos permanecen en el repositorio privado `ALOCAM`, en la carpeta `pwa/`, que es la fuente de la que se copia este contenido.

La carcasa no procesa datos de ALOCAM ni almacena sesión, tokens o respuestas: solo carga la Web App autenticada dentro de un `<iframe>` y permite instalarla como aplicación.
