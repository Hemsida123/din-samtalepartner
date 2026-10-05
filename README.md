# Din Samtalepartner – Saphira Bjørnå

Komplett statisk webbplats med 13 sidor, mobilmeny, tjänster, priser, presentation, forskning, arkiverade arrangemang och kontaktuppgifter. Bilder och typsnitt ligger lokalt.

## GitHub Pages

Ladda upp hela innehållet i `dist/` till ditt GitHub-repository. Behåll alla undermappar. `index.html` ska ligga i roten tillsammans med `style.css`, `fonts.css`, `app.js` och `assets/`. Aktivera GitHub Pages från repositoryts huvudgren och rotmapp. `.nojekyll` ingår. Ingen installation eller byggprocess behövs för den färdiga webbplatsen.

ZIP-paketet innehåller redan innehållet i `dist/`, så ladda upp filerna direkt efter uppackning. Länkar är relativa och fungerar även när webbplatsen ligger i en undermapp på GitHub Pages.

## Kontakt och bokning

Telefon- och e-postknappar öppnar besökarens egna appar. Bokningsknappar öppnar kundens befintliga bokningskalender. Webbplatsen har inget eget formulär, betalsystem eller insamling av besökaruppgifter.

## Innehåll och ändringar

Innehåll baseras på kundens offentliga webbplats https://www.dinsamtalepartner.com/ och länkade tjänstesidor, kontrollerat 5 oktober 2026. Bilderna kommer från samma webbplats. Bekräfta aktuella priser, öppettider och bokningsvillkor med kunden före extern lansering.

För att ändra färdiga sidor: redigera respektive HTML-fil, `style.css` och `app.js`. I källprojektet kan HTML-filerna återskapas med `python3 build.py` (kräver BeautifulSoup). `home-base.html` innehåller sidhuvud och startsidans hero. Texten för övriga sektioner och undersidor finns i `build.py`.
