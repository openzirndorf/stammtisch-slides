# OpenZirndorf — Erster Stammtisch Präsentation

Statische Reveal.js-Präsentation für den ersten OpenZirndorf Stammtisch am **11. März 2026**.

🔗 **Live:** https://openzirndorf.github.io/stammtisch-2026/

## Lokal öffnen

Einfach `index.html` im Browser öffnen — kein Server, kein Build-Step, kein npm.

## Auf GitHub Pages deployen

1. Repo auf GitHub pushen
2. Settings → Pages → Source: `main` / `root`
3. Fertig — läuft unter `https://<org>.github.io/<repo>/`

## Memes hinzufügen

Erstelle die Memes auf [imgflip.com](https://imgflip.com) und speichere sie als PNG in `assets/`:

| Dateiname | Meme | Slide |
|-----------|------|-------|
| `meme-spiderman.png` | Two Spider-Men pointing | 2 |
| `meme-this-is-fine.png` | This is fine (Hund im Feuer) | 3 |
| `meme-surprised-pikachu.png` | Surprised Pikachu | 5 |
| `meme-tell-me-about-yourself.png` | Job Interview | 6 |
| `meme-shut-up-take-my-money.png` | Futurama Fry | 7 |
| `meme-we-did-it-patrick.png` | SpongeBob & Patrick | 10 |

Fehlt ein Bild, wird ein Platzhalter angezeigt — die Präsentation bleibt vollständig nutzbar.

## Navigation

| Taste | Aktion |
|-------|--------|
| `→` / `Space` | Nächste Folie |
| `←` | Vorherige Folie |
| `F` | Vollbild |
| `S` | Speaker Notes (falls vorhanden) |
| `Esc` | Übersicht aller Folien |

## Technologie

- [Reveal.js 5.1](https://revealjs.com/) via CDN — keine lokalen Abhängigkeiten
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) via Google Fonts
- Kein Build, kein npm, kein Framework
