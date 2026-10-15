# Ricocat · Landing

Sitio estático, sin build.

## Estructura
- `index.html` — landing completa
- `support.js` — runtime (carga React 18 desde unpkg)
- `assets/` — imágenes y SVG (61 archivos)
- `vercel.json` — caché de assets y headers

## Deploy en Vercel
**Opción A — arrastrar:** vercel.com/new → "Deploy" → arrastra esta carpeta.

**Opción B — CLI:**
```
npm i -g vercel
cd vercel
vercel --prod
```
Framework preset: **Other**. Build command: vacío. Output directory: `.` (raíz).

**Opción C — GitHub:** sube el contenido de esta carpeta a un repo e impórtalo en Vercel con los mismos ajustes.

## Pendientes de contenido
- Links reales: "Dónde comprar", redes sociales, botones "Comprar".
- Catálogo completo (hoy hay 9 productos repetidos hasta 16).
