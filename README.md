# Swissintell — 2026 Redesign

Rediseño de la web institucional de [Swissintell](https://swissintell.ch) — asociación suiza de inteligencia económica, con base en EPFL Innovation Park, Lausanne.

## Contenido

Sitio de una sola página (`index.html`) con:

- **Hero full-bleed** con foto de los Alpes suizos y badges flotantes animados
- **Services** (Press Review, Events, Publications) con tarjetas oscuras
- **Our Events** con fotos reales
- **Testimonials**, **timeline** histórico, **CTA** de membresía
- **Press / blog** y **footer** completo
- **Selector de idioma flotante** (EN · FR · DE) fijo en el scroll

## Ejecutar localmente

Basta con un servidor estático:

```bash
# Python 3
python -m http.server 8000

# o Node
npx serve .
```

Abrir `http://localhost:8000`.

## Estructura

```
.
├── index.html               # Sitio completo (HTML + CSS + JS inline)
├── assets/
│   ├── swissintell-logo.png # Logo oficial
│   ├── swissintell-logo.svg
│   ├── swiss-alps.jpg       # Fondo del hero
│   └── event-*.jpg          # Fotografías de la sección Events
└── README.md
```

## Paleta

| Token | Valor | Uso |
|---|---|---|
| `--red` | `#E01A27` | Color de marca |
| `--red2` | `#B8101C` | Hover / énfasis |
| `--ink` | `#0b0f1a` | Tipografía principal, bloques oscuros |
| `--bg` | `#faf7f0` | Fondo crema |
| `--line` | `#e5e0d6` | Bordes |

## Tipografía

- **Plus Jakarta Sans** (400–800) — texto e interfaz
- **Caveat** — acentos manuscritos ("Bonjour!", comillas)

## Licencia

© 2026 Swissintell. Todos los derechos reservados.
