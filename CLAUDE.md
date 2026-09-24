# CLAUDE.md — Norvanda Fisioterapia

## Proyecto
Sitio comercial de Norvanda Fisioterapia (equipamiento/tecnología para clínicas de fisioterapia y rehabilitación).
- Repo: `T-bird214/Norvanda` · Vercel: `norvanda-fisioterapia` → https://norvanda-fisioterapia.vercel.app
- Copia local: `~/Documentos/Proyeco-Norvanda/norvanda-web`. Documentos del negocio (propuesta, estrategia, prototipo) en `~/Documentos/Proyeco-Norvanda/`, fuera del repo.
- Dueño: Daniel. Entorno: Fedora + zsh. Navegador: Brave (Flatpak).

## Stack
Sitio estático: `index.html` único (HTML/CSS/JS vanilla) + `assets/`, `robots.txt`, `sitemap.xml`. Sin build ni dependencias.

## REGLAS FIJAS
- Nunca muestres valores de tokens, claves ni secretos. Solo nombres de variables.
- Trabaja por fases. Al final de cada fase, muestra un resumen y ESPERA el "ok" antes de seguir.
- Nada destructivo sin confirmación: no borres archivos, ramas ni repos, no hagas force push, no reescribas el historial.
- En el repo, todos los cambios van en una rama nueva, con un Pull Request. No hagas push directo a `main`.
- Para cualquier login interactivo, da el comando exacto y Daniel lo corre en otra terminal.
- Cambios de código de la app solo con aprobación explícita y en PR separado.

## Convenciones
- Commits en español, estilo `tipo: descripción` (feat, fix, chore, docs, ci).
- Ramas: `feature/…`, `fix/…`, `chore/…`, `docs/…`.
