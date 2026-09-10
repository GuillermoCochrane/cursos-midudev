# HTML Lab — Aprendizaje incremental de HTML moderno

Laboratorio personal para aprender HTML desde cero, basado en el curso
de [Midudev](https://www.youtube.com/watch?v=3nYLTiY5skU). Un único `index.html` que evoluciona commit a commit.

> No es un curso consumido. Es un historial de aprendizaje.

---

## Filosofía de trabajo (mía)

- **Un único `index.html` de laboratorio.** No creo una página nueva por
  capítulo. Enriquezco la misma página desde los fundamentos hasta `<dialog>`.
- **Git como historial de aprendizaje**, no solo como backup. Dentro de
  seis meses quiero poder mirar `git log` y ver exactamente qué aprendí
  y cómo evolucionó el código.
- **Ciclo por bloque:** ver → implementar/experimentar → modificar código
  → probar en el navegador → commit.
- **El video es un roadmap de commits**, no una lista de capítulos para
  tildar. No commiteo por haber mirado. Commiteo por haber construido.
- **Cada commit deja el proyecto abrible y funcional.** Si un commit rompe
  algo, ese sprint fue demasiado grande o mal cerrado.

## Rigor técnico (del plan híbrido)

- **Timestamps verificados** contra el índice real del video.
- **Checkpoints verificables:** cada commit tiene un entregable concreto
  que se puede comprobar en el navegador.
- **Convención de commits:** `tipo(scope): mensaje`
  - `chore` setup · `feat` funcionalidad · `style` estilos
  - `docs` documentación · `refactor` mejora sin cambio de comportamiento
- **Tags de checkpoint:** `git tag checkpoint-01`, etc.
- **Granularidad:** ~8–10 min por commit. Si un commit se siente pesado,
  se desdobla.

---

## Roadmap de commits

- [x] **01**: `index.html` abre en el navegador con estructura mínima
- [x] **02**: contenido estructurado con jerarquía
- [x] **03**: imágenes e inputs correctos, sin malas prácticas
- [x] **04**: uso correcto de atributos e identificadores
- [ ] **05**: documento completo con head/body, charset, viewport, favicon
- [ ] **06**: metaetiquetas SEO y primeros estilos inline
- [ ] **07**: estructura semántica sin divs innecesarios
- [ ] **08**: navegación y enlaces correctos, accesibilidad básica
- [ ] **09**: enlaces especiales y atributos de listas
- [ ] **10**: formulario funcional con fieldset, label e input
- [ ] **11**: formulario validado con controles extra nativos
- [ ] **12**: controles interactivos y multimedia integrados
- [ ] **13**: recursos optimizados y iframe embebido
- [ ] **14**: modal funcional con `<dialog>`
- [ ] **15**: README completo y apuntes finales

---

## Estructura del repositorio

```
/
├── index.html          # laboratorio único, evoluciona con cada commit
├── assets/
│   └── images/
│       └── profile.jpg
└── README.md           # este archivo
```

---

## Conceptos que quiero dominar al final

- [ ] Diferencia entre `<div class="header">` y `<header>`
- [ ] Diferencia entre `<input type="submit">` y `<button type="submit">`
- [ ] Por qué `<dialog>` reemplaza modales hechos con divs + JS
- [ ] Cuándo usar `section`, `article` y `aside` (y cuándo no)
- [ ] Qué hace cada metadato del `<head>` y por qué importa
- [ ] Atributos booleanos: por qué `disabled` y no `disabled="true"`

---
