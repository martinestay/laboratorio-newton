# Principia

Laboratorio de física en 3D que funciona en el navegador, en español, para computador y celular. Empujas bloques, cuelgas péndulos, lanzas satélites y ves en vivo las fuerzas, la energía y las fórmulas de lo que está pasando.

El nombre viene de los *Philosophiæ Naturalis Principia Mathematica*, la obra de 1687 en la que Newton publicó sus leyes del movimiento y la gravitación universal.

## Qué trae

| Sección | Escenarios |
|---|---|
| Dinámica (Newton) | 27 |
| Energía y trabajo | 10 |
| Cantidad de movimiento | 8 |
| Rotación y momento angular | 8 |
| Ondas y oscilaciones | 8 |
| Gravitación y órbitas | 7 |
| Fluidos | 6 |
| Sistemas de referencia | 5 |

Algunos escenarios aparecen en más de una sección; en total son 69 distintos. Además:

- **53 objetos** en un inventario tipo Minecraft, con una barra propia para cada sección.
- **38 desafíos:** el juego te da los datos, tú calculas el resultado y la simulación lo comprueba.
- **Dos modos:** Básico (física sin cálculo) y Avanzado (derivadas, integrales, aire, cuerdas elásticas y métodos numéricos).
- **Herramientas de estudio:** diagramas de cuerpo libre, gráficos, fórmulas con los valores reemplazados, calculadora y referencias bibliográficas.

## Controles

| Acción | Computador | Celular |
|---|---|---|
| Moverse | `W` `A` `S` `D` (`Shift` para correr) | Joystick (hasta el borde para correr) |
| Saltar | `Espacio` | Saltar |
| Girar la cámara | Arrastrar el mouse | Arrastrar en la escena |
| Acercar la cámara | Rueda del mouse | `+` y `−`, o pellizcar |
| Empujar | `E` | Empujar |
| Patear una bola | `F` | Patear |
| Subir o bajar del auto | `R` | Auto |
| Elegir objeto de la barra | `1` a `9` | Tocar la casilla |
| Seleccionar y mover | `0` | Tocar la flecha |
| Abrir el inventario | `I` | Tocar el maletín |
| Pausa | `P` | Botón de pausa |
| Cámara en 1ª o 3ª persona | `V` | Menú ☰ |
| Ocultar todos los cuadros | `H` | Menú ☰ |

## Requisitos y rendimiento

- Un navegador actualizado con WebGL: Chrome, Edge, Firefox o Safari.
- Conexión a internet al abrirlo, porque carga Three.js r128 desde cdnjs y las fuentes desde Google Fonts.
- En **Vista → Rendimiento** se elige entre Ahorro (30 cuadros por segundo), Normal (60, el valor por defecto) y Alta (60, con resolución Retina completa).

## Privacidad

Principia no tiene servidor ni cuentas. El progreso de los desafíos y la configuración quedan solo en el navegador de cada persona (localStorage). Eso sí, al abrir la página, el navegador se conecta a cdnjs y a Google Fonts para descargar el motor 3D y las fuentes.

## Archivos

- `index.html`: el juego completo, en un solo archivo. No hay nada que compilar.
- `LEEME.md`: este documento.

## Cómo publicarlo

Sirve cualquier hosting de páginas estáticas. Estas tres opciones son gratuitas.

### Netlify Drop (la más rápida)

1. Entra a https://app.netlify.com/drop
2. Arrastra **esta carpeta** (`publicar`) a la página.
3. Crea una cuenta y reclama el sitio para que el enlace no caduque. Ahí puedes cambiar el nombre, por ejemplo a `principia`, si está disponible.

### GitHub Pages

Esta carpeta ya es un repositorio de git, pero todavía no está conectada a GitHub.

1. Crea en GitHub un repositorio vacío llamado `principia`.
2. Conéctalo y súbelo, reemplazando `TU-USUARIO`:

   ```bash
   git remote add origin https://github.com/TU-USUARIO/principia.git
   ```

   ```bash
   git push -u origin main
   ```

3. En el repositorio entra a **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. Queda en `https://TU-USUARIO.github.io/principia/`.

### itch.io (página de juegos, con comentarios y estadísticas)

1. Crea un proyecto en https://itch.io/game/new y en «Kind of project» elige **HTML**.
2. Sube `principia-web.zip`, que está junto a esta carpeta, y marca «This file will be played in the browser».
3. Elige un tamaño de ventana, por ejemplo 1280 × 800, y activa «Fullscreen button» y «Mobile friendly».
4. Publícalo como **Public**.

## Cómo actualizarlo

Reemplaza `index.html` en el mismo sitio y el enlace no cambia:

- **Netlify:** vuelve a arrastrar la carpeta en la sección Deploys de tu sitio.
- **GitHub:** guarda el cambio con un commit y haz `git push`.
- **itch.io:** sube un zip nuevo.

## Licencia

Todavía no tiene una licencia definida. Mientras no se agregue una, quien lo visite puede usarlo, pero no tiene permiso explícito para copiar o modificar el código.

## Créditos

Creado por Martín Estay Valdés con la ayuda de Claude Opus 5.5, de Anthropic. Las fuentes de la física están en la pestaña **Referencias** del juego.
