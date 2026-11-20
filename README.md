# GFW Workspace — Website

Officiële informatieve website voor **gfw-workspace.nl**, het digitale samenwerkingsdomein van **RKVV Gesta** voor het **GaldersFeestWeekend (GFW)**.

De website wordt gehost via GitHub Pages en geeft informatie over de vereniging, het evenement, Google Workspace en de officiële contactgegevens.

**Website:** https://gfw-workspace.nl  
**Organisatie:** RKVV Gesta  
**Hosting:** GitHub Pages

## Functionaliteiten

- Ondersteuning voor Nederlands (NL) en Engels (EN).
- Responsive ontwerp voor desktop, tablet en mobiel.
- Vijf afzonderlijke pagina's met duidelijke navigatie.
- Rechtstreekse toegang tot Google Workspace voor bevoegde vrijwilligers.
- Officiële organisatiegegevens en contactadressen.
- Beveiligde HTTPS-verbinding via GitHub Pages.

## Pagina's

| Pagina | URL |
|---|---|
| Home | `/` |
| RKVV Gesta | `/rkvv-gesta/` |
| GaldersFeestWeekend | `/galdersfeestweekend/` |
| Google Workspace | `/google-workspace/` |
| Contact & gegevens | `/contact/` |

De oude routes `/organisatie/` en `/workspace/` worden niet meer gebruikt.

## Projectstructuur

```text
gfw-workspace-website/
├── index.html
├── rkvv-gesta/
│   └── index.html
├── galdersfeestweekend/
│   └── index.html
├── google-workspace/
│   └── index.html
├── contact/
│   └── index.html
├── assets/
│   ├── style.css
│   └── site.js
├── gesta-logo.png
├── CNAME
├── .nojekyll
└── README.md
```

## Beheer en onderhoud

De website bestaat uit statische HTML-, CSS- en JavaScript-bestanden.

| Bestand | Functie |
|---|---|
| `index.html` | Homepage |
| `assets/style.css` | Vormgeving en mobiele weergave |
| `assets/site.js` | Vertalingen en taalwissel |
| Overige `index.html`-bestanden | Inhoud van de afzonderlijke pagina's |
| `CNAME` | Koppeling met het domein |

Wijzigingen worden via de `main`-branch automatisch gepubliceerd door GitHub Pages.

**GitHub Pages-configuratie:**
- Branch: `main`
- Publicatiemap: `/(root)`
- Domein: `gfw-workspace.nl`
- HTTPS: ingeschakeld

## Google Workspace

Google Workspace wordt gebruikt voor de interne samenwerking en documentopslag van de GFW-vrijwilligerscommissies.

Via de Workspace-knop op de website kunnen bevoegde gebruikers de gedeelde Google Drive-omgeving openen.

De toegangsrechten worden afzonderlijk beheerd binnen Google Workspace. De website verleent zelf geen toegang tot vertrouwelijke bestanden.

## Beveiliging

Deze repository is openbaar. De broncode kan door iedereen worden bekeken, maar alleen gebruikers met de juiste GitHub-rechten kunnen rechtstreeks wijzigingen doorvoeren.

Er worden geen wachtwoorden, API-sleutels, toegangstokens of vertrouwelijke documenten in deze repository opgeslagen.

## Projectinformatie

**Organisatie:** RKVV Gesta  
**Evenement:** GaldersFeestWeekend (GFW)  
**Website:** https://gfw-workspace.nl  
**Repository:** `RKVVGesta-GFW/gfw-workspace-website`

---

*Deze website is bedoeld voor publieke informatie over RKVV Gesta, GaldersFeestWeekend en de digitale samenwerking via Google Workspace.*
