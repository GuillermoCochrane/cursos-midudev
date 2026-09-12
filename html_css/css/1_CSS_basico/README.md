# CSS Básico — Aprendizaje incremental

Laboratorio de CSS basado en el curso de Midudev.
Parte del monorepo `html_css/`. Continuidad directa del curso de `html/`:
se reutiliza el mismo `index.html`.

> Ver → implementar → probar → commit. Git como historial de aprendizaje.

---

## Roadmap de checkpoints

- [x] **01** `-----------------` — `index.html` copiado desde `html/`, limpio de comentarios
- [x] **02** `00:00:00–00:17:08` — Introducccion: estilos básicos inline
- [x] **03** `00:17:08–00:28:03` — Colores, transparencia y currentColor
- [x] **04** `00:28:03–00:32:35` — Selectores de clase e ID
- [x] **05** `00:32:35–00:42:17` — Herencia: `inherit`, `initial`, `unset` y `revert`
- [ ] **06** `00:42:17–00:49:40` — Pseudoclases: `hover`, `focus`, `first-child`, `last-child`, etc.
- [ ] **07** `00:49:40–01:02:52` — descendientes, hijos y hermanos
- [ ] **08** `01:02:52–01:08:04` — reglas que se sobrescriben y fallbacks
- [ ] **09** `01:08:04–01:18:37` — resolución de conflictos y `!important`
- [ ] **10** `01:18:37–01:24:26` — `px`, `em`, `rem`, `%`, `vw`, `vh`
- [ ] **11** `01:24:26–01:27:00` — base consistente entre navegadores
- [ ] **12** `01:27:00–01:34:40` — comprensión del box model
- [ ] **13** `01:34:40–01:40:35` — propiedades aplicadas correctamente
- [ ] **14** `01:40:35–01:42:24` — control de tamaño con `border-box`

---

## Estructura

```
1_CSS_basico/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── images/
└── README.md
```

---

## Conceptos que quiero dominar

- [ ] Por qué la cascada y la especificidad se llaman así
- [ ] Diferencia entre `em` y `rem`
- [ ] Cuándo usar `!important` (y cuándo no)
- [ ] Qué hace `box-sizing: border-box` y por qué es el default moderno
- [ ] Diferencia entre `margin` y `padding`
- [ ] Por qué existen reset y normalize
- [ ] Diferencia entre `>` y ` ` (espacio) como combinadores
- [ ] Qué es `currentColor` y cuándo usarlo

---

- `assets/css/styles.css` creado y enlazado