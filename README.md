# Laboratorio Newton: cómo publicarlo

Esta carpeta tiene todo lo necesario: el juego completo está en `index.html`, un solo archivo.

- **Qué necesita:** cualquier hosting de páginas estáticas. No hace falta servidor, base de datos ni compilar nada.
- **Qué carga de internet:** el motor 3D (Three.js, desde cdnjs) y las fuentes (desde Google Fonts). Por eso, quien lo abra necesita conexión.
- **Qué guarda:** el progreso de los desafíos y la configuración quedan solo en el navegador de cada persona (localStorage). No se envía nada a ningún servidor.

## Opción 1: Netlify Drop (la más rápida, gratis)

1. Entra a https://app.netlify.com/drop
2. Arrastra **esta carpeta**  a la página.
3. En unos segundos te da un enlace público del tipo `https://nombre-al-azar.netlify.app`.
4. Para que el enlace no caduque, crea una cuenta gratis y reclama el sitio. Ahí puedes cambiarle el nombre, por ejemplo `laboratorio-newton.netlify.app`.

## Opción 2: GitHub Pages (gratis, queda en tu cuenta de GitHub)

1. Crea un repositorio nuevo, por ejemplo `laboratorio-newton`, y sube `index.html`.
2. En el repositorio entra a **Settings → Pages**.
3. En «Source» elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. Al minuto queda publicado en `https://TU-USUARIO.github.io/laboratorio-newton/`.

## Opción 3: itch.io (página de juegos, con comentarios y estadísticas)

1. Crea un proyecto nuevo en https://itch.io/game/new
2. En «Kind of project» elige **HTML**.
3. Sube el archivo `laboratorio-newton-web.zip`, que está junto a esta carpeta, y marca «This file will be played in the browser».
4. Elige un tamaño de ventana, por ejemplo 1280 × 800, y activa «Fullscreen button» y «Mobile friendly».
5. Publícalo como **Public**.

## Para actualizar más adelante

Reemplaza `index.html` por la nueva versión en el mismo sitio:

- **Netlify:** vuelve a arrastrar la carpeta en la sección Deploys de tu sitio.
- **GitHub:** sube el archivo nuevo.
- **itch.io:** sube un zip nuevo.

El enlace no cambia.

---

Creado por Martín Estay Valdés con la ayuda de Claude Opus 5.5, de Anthropic.
