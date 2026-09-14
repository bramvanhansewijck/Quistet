# Quistet — de quiz van District 21

Website voor Quistet.be: een interactieve gameshowquiz in Boom.

De website kondigt Quistet aan als **weldra beschikbaar bij District 21 Escape Rooms in Boom**. Ze introduceert de gameshow, de zes spelersdesks, de AI-host, de spelvormen en het duelpodium. Er is nog geen openingsdatum, prijs of boekingsmogelijkheid aangekondigd.

## Publicatie op de bestaande hosting

Dit is een zelfstandige statische website, zonder installatie of build. De hosting wordt extern beheerd; deze repository wijzigt geen serverinstellingen of DNS-records.

1. Haal de nieuwste `main` van deze repository op in de bestaande checkout: `git pull --ff-only origin main`.
2. Publiceer `index.html`, `styles.css`, `script.js`, `robots.txt`, `sitemap.xml` en de volledige map `assets/` in de reeds ingestelde documentroot van Quistet.be. `index.html` vervangt de huidige tijdelijke pagina. Als de documentroot rechtstreeks naar de checkout wijst, volstaat het bijwerken van die checkout.
3. Behoud bestaande serverconfiguratie. Publiceer de `.git`-map niet. Wis een eventuele pagina- of CDN-cache voor de gewijzigde bestanden.
4. Controleer `https://quistet.be/` en controleer dat afbeeldingen en lettertypes uit `assets/` laden.

Het bijwerken van GitHub bewijst op zichzelf niet dat de externe webserver is bijgewerkt.

## Inhoud aanpassen

- Teksten en links: `index.html`.
- Huisstijl en mobiele weergave: `styles.css`.
- Mobiel menu en jaartal: `script.js`.
- Contact: `info@district21.be`, `+32 485 57 53 50`.
- Locatie: Hoek 120, 2850 Boom.

De uitklapbare spelrondes werken ook zonder JavaScript. Het contactadres opent het e-mailprogramma; de website verstuurt of bewaart zelf geen berichten. Er zijn geen trackers, externe lettertypeaanvragen, cookies of nieuwsbriefinschrijvingen toegevoegd.

## Originele projectbeelden

- `assets/quistet-logo.png`: het originele **Quistet quizlogo van District 21**, goedgekeurd op 2 september 2026. Het logo is ongewijzigd overgenomen.
- `assets/quistet-arena.webp`: het bestaande projectbeeld **Quistet quizruimte met duelpodium** van 3 september 2026, geoptimaliseerd voor het web. Dit is een conceptbeeld, geen foto van een afgewerkte ruimte; dat wordt op de pagina vermeld.
- `assets/district21-logo.jpg`: het bestaande D21-logo van de District 21-website.
- `assets/favicon.svg`: eenvoudig Q-beeldmerk voor kleine browsericonen, in de kleuren van Quistet.

De beelden en merknamen behoren bij het project en krijgen via deze repository geen aparte open licentie.

Barlow en Barlow Condensed worden lokaal aangeboden onder de SIL Open Font License; zie `FONT-LICENSE.txt`. De lettertypes zijn van Jeremy Tribby en komen uit Google Fonts.
