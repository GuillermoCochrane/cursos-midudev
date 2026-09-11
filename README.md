# Cursos de Midudev — Ejercicios

Repositorio personal con los ejercicios de los cursos de programación
de [Midudev](https://www.youtube.com/@midudev) disponibles en YouTube.

Cada curso vive en su propia carpeta y avanza a medida que avanzo con
los videos. Dentro de cada curso, los ejercicios se organizan por
módulo, en subcarpetas numeradas.

---

## Estructura

```
/
├── html_css/          # cursos secuenciales de HTML y CSS
│   ├── html/          # curso de HTML
│   └── css/           # curso de CSS, dividido por módulos
│       ├── 1_CSS_basico/
│       ├── 2_Flexbox/
│       ├── 3_Grid/
│       └── 4_Animaciones/
├── fullstack/         # pendiente
└── react/             # pendiente
```

---

## Cursos

- [x] **HTML** — [ver laboratorio](html_css/html/README.md) · cerrado
- [ ] **CSS básico** — [ver laboratorio](html_css/css/1_CSS_basico/README.md) · en progreso
- [ ] **CSS Flexbox** — pendiente
- [ ] **CSS Grid** — pendiente
- [ ] **CSS Animaciones** — pendiente
- [ ] **Fullstack** — pendiente
- [ ] **React** — pendiente

---

## Convenciones

- **Commits:** `tipo(curso[/módulo]): mensaje`
  - Ejemplos: `feat(html): dialog nativo`, `feat(css/basico): box-sizing`
- **Tags:** uno por curso, al cierre (`html`, `css-basico`, ...)
- **Un `index.html` por laboratorio**, que evoluciona commit a commit.
- **Cada commit deja el proyecto abrible en el navegador.**

---

## Filosofía

No es un repo de cursos consumidos. Es un historial de aprendizaje:
cada commit representa un bloque de contenido comprendido e implementado,
no un video mirado.
