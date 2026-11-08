# Basismodel websites

Herbruikbaar startpunt voor drie bedrijfswebsites, gebouwd tijdens mijn opleiding tot full stack developer.

- Een schrijnwerkerij (massieve parketvloeren en trappen)
- Een karweizaak
- Een kinesitherapiepraktijk (neurokine en bekkenbodem)

Eerst bouwen we één gedeeld model in HTML, CSS en JavaScript. Daarna maken we per zaak een kopie en vullen we die met de juiste inhoud, kleuren en foto's.

**Auteurs:** Michael Rohart
**Repository:** (https://github.com/michael5rohart/Basis_model.git) 
**Status:** in opbouw

## Doel

Een nette, herbruikbare mal maken die later per zaak wordt aangepast. TypeScript, Node, Express en MongoDB komen later bij, voor onder meer formulieren. Ze vervangen dit model niet.

## Pagina's

Elke site start met dezelfde bestanden. Niet elke pagina blijft voor elke zaak hetzelfde.

| Bestand | Bedoeling | Per zaak |
| --- | --- | --- |
| `index.html` | Homepagina | Altijd, met eigen intro en foto's |
| `diensten.html` | Wat de zaak aanbiedt | Altijd, andere diensten per zaak |
| `realisaties.html` | Foto's van uitgevoerd werk | Vooral schrijnwerkerij en karweizaak. Bij de kinepraktijk vervangen we dit bijvoorbeeld door uitleg over ziektebeelden of soorten therapie |
| `over-ons.html` | Wie jullie zijn | Altijd |
| `contact.html` | Bereikbaarheid | Altijd (telefoon, mail, adres) |
| `privacy.html` | Privacyverklaring | Altijd, later per zaak ingevuld |

Als een pagina voor een zaak niet past, verwijderen of hernoemen we die in die kopie. In het basismodel blijven alle pagina's staan.

## Mappen

[basis_model]/
├── index.html
├── diensten.html
├── realisaties.html
├── over-ons.html
├── contact.html
├── privacy.html
├── css/
├── js/
├── img/
├── docs/
│   ├── logboek.md
│   └── todo.md
└── README.md

## Werken in Git
git add .
git status
git commit -m "Korte uitleg van wat je veranderde"
git push

### Branches
We werken niet rechtstreeks op `main`. `main` blijft de stabiele versie. Voor nieuw werk maak je een extra branch.
```
git branch
git checkout -b html-skelet
```
`git branch` toont op welke tak je zit. `git checkout -b html-skelet` maakt een nieuwe branch en zet je er meteen op. Kies een duidelijke naam, zoals `readme` of `css-layout`.
Daarna gewoon committen en de eerste keer zo pushen:
```
git add .
git commit -m "Korte uitleg van wat je veranderde"
git push -u origin html-skelet
```
De keren erna volstaat `git push`.
Als het werk klopt, voeg je de branch samen met `main`:
```
git checkout main
git pull
git merge html-skelet
git push
```
Samenwerken kan ook via een pull request op GitHub: daar bekijk je de verschillen eerst, en pas daarna komt de code in `main`.
