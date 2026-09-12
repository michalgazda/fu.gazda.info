# fu.gazda.info — Firma Wykończeniowa Andrzej Gazda

Strona firmowa dla **Andrzeja Gazdy** — wykończanie i remonty wnętrz w Dębicy i okolicach.

Stack: **Astro 7** | Hosting: **GitHub Pages** (auto-deploy z `main`)

## Struktura

- `/` — Strona główna
- `/zakres-uslug/` — Lista usług
- `/galeria/` — Galeria zdjęć (sufity, ściany, płytki, podłogi)
- `/o-firmie/` — O firmie
- `/kontakt/` — Kontakt

## Komendy

| Komenda | Opis |
|---|---|
| `npm run dev` | Dev server (localhost:4321) |
| `npm run build` | Budowa do `dist/` |
| `npm run preview` | Podgląd zbudowanego `dist/` |

## GitHub Pages

Push na `main` → GitHub Actions buduje i deployuje na `https://michalgazda.github.io/fu.gazda.info/`.

## Obrazy

Galeria: `public/images/gallery/` — 34 zdjęcia.

## Migracja

Przeniesiono ze starego WordPress (fu.gazda.info) do statycznego Astro.