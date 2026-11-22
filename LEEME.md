# r3v3rs3 RUN

Juego de navegador para el README de Peterson Sena. Corre con un velocista 3D, supera varios niveles y evita que Black Flash te alcance.

## Jugar
Abre `index.html` en un navegador moderno. No necesita instalación, cuentas, servidores ni dependencias externas.

- `Espacio` o `↑`: saltar.
- `↓` o `S`: deslizarse bajo barreras.
- `P`: pausar o continuar.
- En móvil: toca la pantalla para saltar.
- Recoge los rayos para sumar 50 puntos y alejar a Black Flash.
- Cada nivel cambia el ambiente y acelera la carrera. Black Flash aparece en el nivel 2.

El récord se guarda en el navegador local.

## Publicarlo en GitHub Pages
1. Crea un repositorio público llamado `r3v3rs3-run` en `petersonsenadevs`.
2. Sube `index.html` y la carpeta `assets` a la raíz del repositorio (no subas el ZIP).
3. En **Settings → Pages**, elige **Deploy from a branch**, `main` y `/(root)`.
4. Al publicarse, el juego estará en `https://petersonsenadevs.github.io/r3v3rs3-run/`.

## Enlazarlo desde el README del perfil
Pega este bloque debajo de los badges. La imagen abre el juego publicado:

```markdown
<div align="center">
  <a href="https://petersonsenadevs.github.io/r3v3rs3-run/">
    <img src="https://raw.githubusercontent.com/petersonsenadevs/r3v3rs3-run/main/assets/game-preview.svg" width="100%" alt="Juega a r3v3rs3 RUN: corre, esquiva y escapa de Black Flash" />
  </a>
</div>
```

GitHub no ejecuta juegos HTML incrustados en un README; por eso la portada enlaza a GitHub Pages.

## Archivos
- `index.html`: juego completo, lógica, controles y estilos.
- `assets/runner-3d.png`: animación de carrera creada a partir de la imagen 3D del velocista.
- `assets/runner-slide.png`: pose 3D encogida y baja para deslizarse bajo las barreras.
- `assets/black-flash-zombie.png`: perseguidor zombi 3D de ojos rojos que aparece en el nivel 2.
- `assets/game-preview.svg`: portada clicable para el README.
