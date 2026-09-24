# Norvanda Fisioterapia — Sitio web

Sitio comercial de **Norvanda Fisioterapia**: equipamiento y tecnología premium para clínicas de fisioterapia, centros de rehabilitación e instituciones, con respaldo clínico-técnico y centro de demostración.

🌐 Producción: https://norvanda-fisioterapia.vercel.app

## Stack

Sitio **estático**: un solo `index.html` con HTML, CSS y JavaScript embebidos. Sin framework, sin dependencias y sin paso de build.

| Capa | Tecnología |
|---|---|
| Frontend | HTML5 + CSS + JavaScript (vanilla) |
| Hosting | Vercel (sitio estático) |

## Estructura

```
index.html        # Página completa (secciones, estilos y scripts)
assets/           # Logos y favicon
robots.txt
sitemap.xml
```

## Correr en local

No requiere instalación. Cualquier servidor estático sirve:

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Despliegue

- Vercel (proyecto `norvanda-fisioterapia`) está conectado a este repo.
- **Preview** en cada Pull Request, **producción** al hacer merge a `main`.
- Si se agrega un dominio propio, actualizar `canonical` en `index.html`, `robots.txt` y `sitemap.xml`.

## Flujo de trabajo

1. Crear rama desde `main` (`feature/…`, `fix/…`, `chore/…`, `docs/…`).
2. Abrir Pull Request y revisar el preview de Vercel.
3. Merge a `main` → deploy a producción.

## Licencia

Código propietario. © Norvanda Fisioterapia. Todos los derechos reservados.
