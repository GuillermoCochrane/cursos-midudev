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
- **Cada commit deja el proyecto ejecutable y funcional.** Si un commit rompe
  algo, ese sprint fue demasiado grande o mal cerrado.

## Rigor técnico (del plan híbrido)

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

- [x] **01** `00:00–12:52`     · abre en el navegador con estructura mínima
- [x] **02** `12:52–15:48`     · contenido estructurado con jerarquía
- [x] **03** `15:48–22:51`     · imágenes e inputs correctos, sin malas prácticas
- [x] **04** `22:51–32:27`     · uso correcto de atributos e identificadores
- [x] **05** `32:27–44:00`     · documento completo con head/body, charset, viewport, favicon
- [x] **06** `44:00–51:01`     · metaetiquetas SEO y primeros estilos inline
- [x] **07** `51:01–1:03:17`   · estructura semántica sin divs innecesarios
- [x] **08** `1:03:17–1:12:04` · navegación y enlaces correctos, accesibilidad básica
- [x] **09** `1:12:04–1:16:08` · enlaces especiales y atributos de listas
- [x] **10** `1:16:08–1:23:51` · formulario funcional con fieldset, label e input
- [x] **11** `1:23:51–1:31:04` · formulario validado con controles extra nativos
- [x] **12** `1:31:04–1:36:29` · controles interactivos y multimedia integrados
- [x] **13** `1:36:29–1:45:40` · recursos optimizados y iframe embebido
- [x] **14** `1:45:40–1:53:32` · modal funcional con `<dialog>`

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

- [x] Diferencia entre `<div class="header">` y `<header>`
- [x] Diferencia entre `<input type="submit">` y `<button type="submit">`
- [x] Por qué `<dialog>` reemplaza modales hechos con divs + JS
- [x] Cuándo usar `section`, `article` y `aside` (y cuándo no)
- [x] Qué hace cada metadato del `<head>` y por qué importa

---
