# CV — Hernán Ríos

Sitio de CV construido con [Hugo Blox](https://hugoblox.com) (tema Résumé),
publicado en GitHub Pages: https://hernan2882.github.io/

## Editar contenido
- Bio / experiencia / skills: `content/authors/admin/_index.md`
- Secciones de la home: `content/_index.md`
- Proyectos: `content/project/<nombre>/index.md` (+ `featured.png`)
- Config general: `config/_default/`

## Publicar
Cada `git push` a `main` dispara el workflow `.github/workflows/deploy.yml`
que construye y publica el sitio automáticamente.
