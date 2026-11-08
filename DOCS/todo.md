# Todo — Basismodel

Overzicht van wat er nog moet gebeuren voor het gedeelde website-model.
Werk van boven naar beneden. Wat af is, vink je af.

---

## Nu bezig

- [x] README invullen (namen, link naar de repo, mappenstructuur controleren)
- [x] README committen en pushen

---

## Stap 1 — Project opzetten

- [x] VS Code, extensies en Git installeren
- [x] GitHub-repo, mappenstructuur en README
  - [x] Mappen `css/`, `js/`, `img/` en `docs/` staan goed
  - [x] HTML-pagina's bestaan: index, diensten, realisaties, over-ons, contact, privacy
  - [x] `docs/logboek.md` en `docs/todo.md` bestaan

---

## Stap 2 — HTML-skelet

- [ ] HTML-skelet van de homepagina
  - [ ] `header`, `nav`, `main`, `footer`
  - [ ] Logo-plek en navigatielinks naar alle pagina's
- [ ] Alle pagina's invullen en valideren
  - [ ] Zelfde opbouw op elke pagina
  - [ ] Controleren met de W3C HTML-validator

---

## Stap 3 — Stijlgids en componenten

- [ ] Stijlgids (`docs/componenten.html`) met hero, dienstenkaart en CTA
- [ ] Galerij, getuigenis, contactformulier en footer
- [ ] Extra's: stappenblok en FAQ (voor later)
- [ ] Componenten documenteren in `docs/componenten.md`
- [ ] BEM-klassen consequent gebruiken (`.card`, `.card__title`, `.card--featured`)

---

## Stap 4 — CSS-architectuur

- [ ] CSS-bestanden aanmaken en in de juiste volgorde laden via `main.css`
- [ ] Reset schrijven
- [ ] Designtokens in `theme.css` (kleuren, lettertypes, afstanden, radius, schaduw)
- [ ] Basis, layout en componenten stylen met enkel variabelen
- [ ] Thematest: tweede tijdelijk thema om te bewijzen dat alleen `theme.css` de huisstijl wisselt

---

## Stap 5 — Responsive

- [ ] Mobile-first basis (eerst ± 360 px)
- [ ] Breakpoints vastleggen en in de README zetten
- [ ] Navigatie: op mobiel ingeklapt, op desktop naast elkaar (Flexbox)
- [ ] Grid-layouts en responsive afbeeldingen

---

## Stap 6 — JavaScript

- [ ] JS-modules opzetten
- [ ] Jaartal in de footer automatisch invullen
- [ ] Smooth scroll
- [ ] Toegankelijk hamburgermenu (`nav.js`)
- [ ] Lightbox voor de fotogalerij
- [ ] Formuliervalidatie met eigen foutmeldingen

---

## Stap 7 — Afronden van het model

- [ ] Toegankelijkheid en SEO
- [ ] Performance en testen
- [ ] Privacytekst voorbereiden (later per zaak invullen)
- [ ] Versie 1.0 van het basismodel
- [ ] Code opkuisen en terugblik

---

## Daarna — Per zaak

Niet doen in het basismodel zelf, wel onthouden:

- [ ] Inhoud verzamelen voor de schrijnwerkerij
- [ ] Inhoud verzamelen voor de karweizaak
- [ ] Inhoud verzamelen voor de kinepraktijk
  - [ ] `realisaties.html` vervangen door uitleg over ziektebeelden of soorten therapie
- [ ] Een kopie van het model per zaak maken
- [ ] Eerste versie online zetten via GitHub Pages

---

## Afspraken

- Eigen teksten en foto's, of materiaal met toestemming / duidelijke licentie
- Geen geheimen in HTML of JavaScript
- Contactformulier-tekst niet met `innerHTML` op de pagina zetten
- Footer: naam, adres, telefoon, e-mail en later ondernemingsnummer