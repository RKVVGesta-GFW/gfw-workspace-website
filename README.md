# GFW Workspace — GitHub Pages website

De actieve pagina’s zijn `/`, `/rkvv-gesta/`, `/galdersfeestweekend/`, `/google-workspace/` en `/contact/`.
De oude routes `/organisatie/` en `/workspace/` zijn verwijderd. Ze verwijzen niet meer door; verwijder deze twee oude mappen ook handmatig uit de bestaande GitHub-repository.

## Upload naar GitHub

1. Maak een back-up van de repository `RKVVGesta-GFW/gfw-workspace-website`.
2. Pak de ZIP uit en upload de **inhoud** (niet de ZIP of overkoepelende map) naar de hoofdmap (`main`) van de repository.
3. Behoud het bestaande `gesta-logo.png` bestand in de hoofdmap; dit ZIP-bestand bevat niet het oorspronkelijke logo.
4. Behoud GitHub Pages op `main` + `/(root)` en het custom domain `gfw-workspace.nl`.
5. Controleer na publicatie alle vijf pagina’s, de nieuwe URL’s en de NL/EN-schakelaar.

### Wat is aangepast
- Consistente browser-tabtitels: `Workspace - ...`.
- Nieuwe URLs voor RKVV Gesta en Google Workspace, zonder doorverwijzing vanaf de oude paden.
- Duidelijker vormgegeven navigatieknoppen, kortere home-titel.
- Contactblokken uitgelijnd, zonder mailknoppen of extra contactadressenlink.
- Footer met dezelfde label-opmaak voor telefoon, e-mail en website, en gelijkmatiger verticale witruimte.
- De elf e-mailadressen op de GFW-pagina zijn behouden.

Dit ZIP-bestand publiceert of wijzigt niet zelfstandig de GitHub-repository.

### Update V7
- De Workspace-knop en de Google Drive-knop verwijzen nu naar de gedeelde Drive-map.
- De bovenste externe links zijn duidelijker, met een donkerrode knop voor de officiële website.
- De NL/EN-schakelaar is één grote knop die bij iedere klik omschakelt.
- Extra ruimte in de mobiele header en donkerrode browser-themakleur. iOS Safari bepaalt zelf of de systeemstatusbalk kan meekleuren.


V8: Mobile header actions are in one row, all exactly 46px high, with compact spacing above the divider.


V9: Compactere mobiele typografie voor koppen, tekst, navigatie, kaarten en footer. Desktop onveranderd.

## V10
Extra 12px witruimte tussen het categorielabel en de vetgedrukte titel in de drie contactblokken. Alleen assets/style.css is gewijzigd t.o.v. V9.

V11: de totale hoogte van de NL/EN-knop is nu exact 46px, gelijk aan de twee links (desktop en mobiel). Alleen assets/style.css is gewijzigd.


V12: linker footerkolom heeft dezelfde compacte regelafstand als de bezoekadres- en contactgegevens. Alleen assets/style.css is gewijzigd.

V13: Onderkant laatste tekstregel in de linker footerkolom wordt op desktop uitgelijnd met de laatste regels in de middelste en rechter kolom. Alleen assets/style.css gewijzigd.


## Favicon

Het browser-tabblad gebruikt `favicon.png` (en `favicon.ico` als fallback). Het zichtbare RKVV Gesta-logo op de website blijft `gesta-logo.png`.
