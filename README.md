# Arlet · 1 añito de reinado

Invitación web al primer cumpleaños de Arlet (15/11/2026) y, en la siguiente fase, galería "Un año de reinado" con una foto por mes.

## Estado
- v0.1 — Invitación web (HTML + CSS vanilla, sin build). Demo en GitHub Pages.
- Pendiente — Galería mensual, cuenta regresiva y confirmación por WhatsApp (migración a Vite + Tailwind v4).

## Estructura
```
index.html                 → invitación (lienzo 540×960, escala al viewport)
assets/arlet.jpg           → foto del retrato
assets/arlet-princesa.svg  → caricatura original
assets/fonts/              → Great Vibes + Cormorant Garamond (woff2, OFL)
```

## Ver en local
Abrir `index.html` en el navegador. Para probar en el móvil en la misma red:
`npx serve .` o `py -m http.server 8080` → `http://<IP-local>:8080`

## Deploy
GitHub Pages desde `master` / raíz. La página lleva `noindex` (no aparece en buscadores).
