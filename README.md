# GFW Workspace — Website

Website voor **gfw-workspace.nl**, het digitale samenwerkingsdomein van **RKVV Gesta** voor **GaldersFeestWeekend (GFW)**. De website wordt gehost via GitHub Pages en is beschikbaar in Nederlands en Engels.

## Pagina's

| Pagina | Pad |
|---|---|
| Home | `/` |
| RKVV Gesta | `/rkvv-gesta/` |
| GaldersFeestWeekend | `/galdersfeestweekend/` |
| Google Workspace | `/google-workspace/` |
| Contact & gegevens | `/contact/` |

## Bestanden en logo's

- `assets/style.css` — vormgeving en mobiele weergave.
- `assets/site.js` — Nederlandse en Engelse teksten en de taalwissel.
- `gesta-logo.png` — bestaand officieel Gesta-logo **voor de websiteheader en het browsertabblad**. Dit bestand moet in de repository behouden blijven.
- `apple-touch-icon.png` — GFW Workspace-icoon voor iPhone/iPad-snelkoppelingen.
- `workspace-icon-192.png` en `workspace-icon-512.png` — GFW Workspace-iconen voor Android/webapp.
- `manifest.webmanifest` — instellingen voor toegevoegde webapps.
- `CNAME` — bevat `gfw-workspace.nl`.

## Publiceren

Upload de inhoud van deze ZIP naar de hoofdmap van de openbare repository `RKVVGesta-GFW/gfw-workspace-website` (branch `main`). Behoud het bestaande `gesta-logo.png`. GitHub Pages gebruikt `main` + `/(root)` en het custom domain `gfw-workspace.nl` met HTTPS.

**Ruim oude bestanden op:** verwijder `favicon.png` en `favicon.ico` uit de GitHub-repository wanneer die nog de GFW Workspace-variant bevatten. De oude mappen `/organisatie/` en `/workspace/` worden niet meer gebruikt en kunnen eveneens verwijderd worden.

Controleer na publicatie de vijf pagina's, taalwissel, browsertabblad en een **nieuw toegevoegde** snelkoppeling op de telefoon. Bestaande snelkoppelingen kunnen het oude icoon bewaren.

## Toegang en beveiliging

De Workspace-knop opent een gedeelde Google Drive. Alleen gebruikers met de juiste Google-rechten kunnen de inhoud bekijken. Deze publieke repository mag geen wachtwoorden, tokens of vertrouwelijke documenten bevatten.


V16: Voettekst links volgt nu dezelfde regelafstand en verticale indeling als bezoekadres en contact op desktop. Alleen assets/style.css gewijzigd.


V17: footer op desktop gebruikt één vaste regelhoogte van 21px in alle drie kolommen; zonder extra witruimte tussen de regels.
