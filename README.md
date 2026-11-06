# Portefølje

Dette er porteføljen min for faget Utvikling Vg2 (del 2). Jeg har laget den ut fra prototypen jeg lagde i del 1.

Siden har en kort intro om meg, en del om hva jeg ser etter, ferdighetene mine, lenker til prosjektene mine på GitHub og et skjema for å kontakte meg. Nettsiden er på norsk.

## Hva jeg har brukt

HTML og Tailwind CSS v4 til siden. Jeg valgte Tailwind fordi jeg synes det er enklere, raskere og finere å jobbe med. Vite kjører dev serveren og bygger siden, og jeg bruker Bun til å installere pakker. Prettier og cspell sjekker formateringen og stavingen.

## Kjøre prosjektet

Du må ha Bun installert.

Installer dependencies:

```bash
bun install
```

Start dev serveren:

```bash
bun run dev
```

Åpne deretter adressen Vite skriver i terminalen.

Alle kommandoene fra `package.json`:

| Kommandoer       | Hva den gjør                                |
| ---------------- | ------------------------------------------- |
| `bun run dev`    | Starter dev serveren                        |
| `bun run format` | Formaterer alt med Prettier                 |
| `bun run spell`  | Sjekker stavingen med cspell                |
| `bun run build`  | Bygger nettsiden til `dist` mappen          |
| `bun run deploy` | Legger `dist` ut på GitHub Pages            |
| `bun run check`  | Kjører build, stavekontroll og format sjekk |

> OBS `vite.config.js` må ha `base: '/Portefolje/'` som navnet på GitHub-repositoriet for at styling og JavaScript skal fungere på GitHub Pages.

## Om koden

Utseendet på siden er laget med Tailwind klasser skrevet rett i `index.html`. Den eneste CSS filen er `style.css`, der jeg har satt opp fargene én gang i `@theme`, slik at jeg kan bruke dem som klasser, for eksempel `bg-om-meg-bg`. Det er enklere på denne måten siden jeg bruker hex koder til fargene.

## Dokumentasjon

- [Tailwind CSS](https://tailwindcss.com/docs)
- [Vite](https://vite.dev/guide/)
- [Bun](https://bun.sh/docs)
- [MDN Web Docs](https://developer.mozilla.org)
- [W3schools HTML](https://www.w3schools.com/html/default.asp)
- [W3schools CSS](https://www.w3schools.com/css/default.asp)
- [WCAG 2.1 checker](https://web-accessibility-checker.com/en/color-contrast-checker)

## Lisens

MIT se [LICENSE](LICENSE).
