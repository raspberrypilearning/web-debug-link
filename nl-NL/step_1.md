Houd er rekening mee dat de tag `<a>` (anchor) wordt gebruikt om een link naar een andere webpagina te maken (niet de tag 'link', die wordt gebruikt om naar bronnen zoals lettertypen te linken).

Controleer ook of je het juiste webadres (URL) hebt voor de eigenschap `href`.

Het gedeelte van een webadres na de domeinnaam (zoals 'projects.raspberrypi.org') is hoofdlettergevoelig, dus zorg ervoor dat de hoofdletters overeenkomen.

In dit voorbeeld wordt correcte HTML gebruikt om te linken naar een webpagina die in een nieuw browsertabblad wordt geopend:

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<a href="https://projects.raspberrypi.org/nl-NL/raspberrypi/web-intro" target="_blank">Maak een webpagina zoals deze!</a>

--- /code ---
