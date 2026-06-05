# Guia de contribucion

Gracias por contribuir a los proyectos de Vanda-SaaS — SmartGO. Esta guia establece las pautas generales para colaborar en cualquier repositorio de la organizacion.

Cada proyecto puede tener su propia guia de contribucion en su `CONTRIBUTING.md`. Si existe, esa prevalece sobre esta.

---

## Flujo de trabajo

1. Crea un issue antes de empezar a trabajar, asi todos saben que alguien esta encargado del tema.
2. Crea una rama con el formato que define cada repositorio (ej: `feature/`, `fix/`, `chore/`).
3. Desarrolla en esa rama con commits atomicos y mensajes claros.
4. Abre un Pull Request hacia la rama principal (`main` o `develop` segun el proyecto).
5. Espera la revision de al menos un companero antes de mergear.

---

## Commits

- Usa [Conventional Commits](https://www.conventionalcommits.org/).
- Formato: `tipo(alcance): mensaje en presente`.
- Tipos comunes: `feat`, `fix`, `chore`, `refactor`, `test`, `docs`, `style`.
- El titulo del commit siempre en ingles.
- Bullets de descripcion en español neutro.
- Ejemplo: `feat(inventario): add supplier quick view drawer`.

---

## Pull Requests

- Completa el template de PR que aparece automaticamente.
- Incluye una descripcion clara de los cambios y el motivo.
- Si el PR soluciona un issue, referencialo con `Closes #123`.
- Asegurate de que los checks (tests, linter, build) pasen antes de pedir revision.

---

## Code Review

- Todos los PRs requieren al menos una aprobacion.
- Las sugerencias se hacen con respeto y fundamento tecnico.
- El autor del PR es responsable de mergear una vez aprobado.
- Si hay cambios solicitados, el autor los resuelve y pide una nueva revision.

---

## Testing

- Todo codigo nuevo debe incluir tests.
- Corre la suite de tests localmente antes de abrir el PR.
- Mantenemos la cobertura de tests existente (no la bajes).

---

## Dudas

Si tienes preguntas, abre un issue en el repositorio correspondiente o consulta con el equipo.
