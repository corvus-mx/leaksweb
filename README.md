# Mexileaks - Astro + GitHub Pages

Este proyecto es un sitio estático construido con [Astro](https://astro.build) y desplegado automáticamente en GitHub Pages usando GitHub Actions.

## ¿Cómo desplegar?

1. Haz push a la rama `main`.
2. El workflow de GitHub Actions generará el sitio y lo publicará en la rama `gh-pages`.
3. Activa GitHub Pages en la configuración del repositorio:
   - Ve a **Settings > Pages**.
   - Selecciona la rama `gh-pages` y la carpeta `/ (root)`.

## Desarrollo local

```bash
pnpm install
pnpm run dev
```

## Configuración importante

- El archivo `astro.config.mjs` debe tener la opción `base` igual a `/<nombre-del-repo>/`, por ejemplo `/mexileaks/`.