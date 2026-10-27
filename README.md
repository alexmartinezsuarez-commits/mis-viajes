# Mis Viajes

App web (PWA) para llevar el registro de los viajes en coche de los viernes y domingos: quién viene, cuánto paga cada uno, cuánto cuesta el diésel ese día y si el viaje sale a cuenta.

- El precio del diésel lo saca de la API pública del Ministerio para la gasolinera elegida en la fecha del viaje.
- Los datos se guardan solo en el navegador del móvil. Usa Ajustes → Exportar para hacer copias.

## Uso local

```bash
node serve.js
```

y abre http://localhost:5180

## Publicación

GitHub Pages publica la carpeta `app/` con el workflow `.github/workflows/pages.yml` en cada push a `main`.
