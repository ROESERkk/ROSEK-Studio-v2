ROSEK Studio — sitio estático para GitHub Pages
================================================

CONTENIDO
- index.html: web completa en un solo archivo.
- .nojekyll: evita procesamiento Jekyll innecesario.

PUBLICAR EN GITHUB PAGES
1. Abre tu repositorio recién creado en GitHub.
2. Pulsa Add file > Upload files.
3. Arrastra index.html y .nojekyll (para ver este último, activa mostrar archivos ocultos en tu explorador).
   También puedes subir index.html por sí solo.
4. Pulsa Commit changes.
5. En el repositorio entra a Settings > Pages.
6. En Build and deployment selecciona Deploy from a branch.
7. Branch: main; folder: /(root). Pulsa Save.
8. Espera a que GitHub Pages publique y abre el enlace que aparece en Settings > Pages.

FUNCIONES Y LÍMITES
- Interfaz responsive en español.
- El archivo se procesa en el navegador mediante FFmpeg WebAssembly.
- Salida MP4/H.264 y AAC opcional.
- FPS de origen es la opción predeterminada; el selector permite 59.94, 60, 29.97 y 30.
- Puede tardar en la primera carga y necesita memoria suficiente.
- No ofrece H.265/HEVC; el build web utilizado no garantiza libx265.
- La lectura de resolución y duración viene del reproductor del navegador. No se presenta como un análisis exacto de FPS variables.
- Requiere conexión a internet para cargar el motor FFmpeg desde CDN.
- No se envía el video a un servidor de ROSEK, aunque el navegador descarga librerías desde CDN.

Si GitHub muestra otro nombre de rama, selecciona la rama principal que usa tu repositorio.
