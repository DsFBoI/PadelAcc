# 🎾 Padelsito

Aplicación web para gestionar torneos de pádel con parejas dinámicas y puntuación individual.

## Características

- **Ranking individual**: cada jugador acumula puntos según sus victorias
- **Parejas dinámicas**: los emparejamientos se generan aleatoriamente cada ronda
- **Registro de resultados**: anota el marcador y los puntos se asignan automáticamente

## Cómo hacer deploy en GitHub Pages

1. Crea un repositorio en GitHub (ej. `padelsito`)
2. Sube el archivo `index.html` a la rama `main`
3. Ve a **Settings → Pages**
4. En **Source**, selecciona `Deploy from a branch` → `main` → `/ (root)`
5. Guarda. En unos segundos tendrás tu URL: `https://tuusuario.github.io/padelsito`

## Uso

1. **Añade jugadores** en la pestaña Ranking
2. **Genera una ronda** en la pestaña Partidos — las parejas se sortean automáticamente
3. **Registra el marcador** de cada partido
4. Los puntos se suman solos al ranking

Los datos se guardan en `localStorage` del navegador.
