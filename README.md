# HIEON — Heb Ik Ecologisch Onderzoek Nodig

Zelf-check-wizard voor particulieren op **hieon.nl**. De bezoeker beantwoordt een paar
vragen en krijgt een indicatie of er ecologisch onderzoek (quickscan, en mogelijk
vervolgonderzoek naar vleermuizen, huismus of gierzwaluw) nodig is, met een funnel naar
Van Der Ham Ecologie.

## Structuur
- `index.html` — de volledige, self-contained wizard (HTML + CSS + JavaScript in één bestand). Geen build-stap, geen externe afhankelijkheden.

## Aanpassen
Bewerk `index.html` en commit. Bij een gekoppelde auto-deploy host (GitHub Pages /
Cloudflare Pages) staat elke push binnen ~1 minuut live.

## Nog te doen richting livegang
- Hosting koppelen (gratis static host) + hieon.nl DNS bij mijndomein
- Formulier koppelen aan een form-service (Web3Forms / Formspree) voor het echte mailen
- Privacyverklaring toevoegen
- Later: postcode -> gemeente/provincie via PDOK, voor inline SMP-/gebiedscheck
