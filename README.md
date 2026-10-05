# Calculadora de Sumas

Una aplicación web interactiva de un solo archivo (HTML/JS/TailwindCSS) que permite sumar múltiples datos numéricos pegados desde cualquier fuente.

## Archivos incluidos
- `index.html`: Contiene toda la estructura, estilos (vía Tailwind CDN) y la lógica en JavaScript de la aplicación.
- `.gitignore`: Archivo estándar para ignorar archivos del sistema operativo o editores al subir el proyecto.
- `README.md`: Este archivo de documentación.

## Cómo desplegar en GitHub Pages
1. Inicializa tu repositorio de Git en la carpeta donde extrajiste estos archivos:
   ```bash
   git init
   git add .
   git commit -m "Commit inicial: Calculadora de sumas"
   ```
2. Crea un nuevo repositorio vacío en GitHub.
3. Sube tus archivos al repositorio remoto:
   ```bash
   git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   git branch -M main
   git push -u origin main
   ```
4. En la página de tu repositorio en GitHub, ve a **Settings** > **Pages**.
5. En la sección "Build and deployment", selecciona "Deploy from a branch".
6. Elige la rama `main` y la carpeta `/ (root)` y haz clic en Save.
7. ¡Listo! En un par de minutos tu página estará disponible en la URL que GitHub te proporcionará.
