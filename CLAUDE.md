# Fernanda Zotti — Landing Page

Repo standalone da landing page de Fernanda Zotti.

## Stack
- React 19 + Vite 6 + Tailwind v4 (@theme) + Framer Motion v12 + @fontsource
- Spectral (display) + Source Sans 3 (sans)
- Paleta: cafe queimado (#5C4033) + dourado envelhecido (#C9985A)

## Comandos
- `npm run dev` — servidor local
- `npm run build` — build de producao
- `npm run preview` — preview do build

## Fotos
Substituir os placeholders em `public/`:
- `foto-hero.jpg` — foto principal (3:4, min 800x1000px)
- `foto-about.jpg` — foto da secao sobre (3:4, min 800x1000px)

Apos substituir, fazer `git push` e o Vercel redeploya automaticamente.

## Dados do cliente
Centralizados em `src/site.config.ts`. Nunca duplicar dados em componentes individuais.
