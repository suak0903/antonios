# Antonio — Website-Entwurf

Unverbindlicher Website-Demonstrator für das Antonio (Antonios Espresso Bar),
Trattoria und Espresso-Bar in der Mönchengladbacher Innenstadt.
Erstellt von Dr.-Ing. Suat Akyol.

Live (GitHub Pages): https://suak0903.github.io/antonios/

## Technik
- Vanilla HTML + CSS + JS, kein Build-Step nötig, kein npm
- Self-hosted Schriften (Cinzel Display + Inter Body), kein Google-CDN
- Kreidetafel-Karte als Hero-Herzstück, Galerie-Masonry mit Lightbox, Scrollspy, mobiles Menü
- Palette aus der echten Marke: Tafel-Schwarzbraun, Marken-Rot, Gold, Tageslicht-Creme
- Strukturierte Daten (Restaurant JSON-LD), noindex (Entwurf)

## Chrome aus einer Quelle
Header, Footer und Demo-Leiste liegen in `partials/` und werden per `node build-site.mjs`
byte-identisch in jede Seite gesetzt (kein Drift). Nach Änderung an einem Partial:
`node build-site.mjs` ausführen, dann committen.

Inhalte und Bilder stammen aus öffentlich verfügbaren Quellen (Google, Facebook). Kein offizieller Auftritt.
