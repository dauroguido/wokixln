# Club LA NACION × Woki

Landing scrolleable de la propuesta de alianza Club LA NACION × Woki: convertir el beneficio gastronómico en una experiencia premium con reserva integrada y data real de redención.

## Stack

HTML estático, sin build step. Una sola página (`index.html`) con:

- Tipografía Mona Sans + Figtree vía Google Fonts
- Iconos Lucide vía CDN
- Logos SVG inline (Club LA NACION + Woki B2B)
- Mobile-responsive con `clamp()` y media queries

## Cómo verlo localmente

```bash
# Abrir directamente
open index.html

# O servir con cualquier static server
python3 -m http.server 8000
# → http://localhost:8000
```

## Estructura

```
.
├── index.html      # Landing completo
├── ln.svg          # Logo Club LA NACION
└── README.md
```

El logo de Woki B2B va embebido inline en `index.html` (no requiere archivo externo).

## Deploy

Vercel, Netlify, GitHub Pages — funciona en cualquier static host. Sin variables de entorno ni dependencias.

```bash
# GitHub Pages
# Settings → Pages → Source: main, /(root)
```

## Secciones

1. Portada
2. Contexto del Club
3. Problema actual
4. Experiencia del socio (mockup `club.lanacion.com.ar` con botón Reservar)
5. Experiencia del restaurante (panel `admin.wokiapp.com`)
6. Valor por stakeholder
7. Upside: yield management + data real
8. Plan de activación en 3 fases
9. Modelo económico
10. Cierre

---

Confidencial · Woki, 2026
