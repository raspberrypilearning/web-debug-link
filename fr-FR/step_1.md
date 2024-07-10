N'oublie pas que c'est la balise '<a>' (ancrage) qui est utilisée pour créer un lien vers une autre page Web (et non la balise 'link', qui est utilisée pour créer un lien vers des ressources telles que les polices).

Vérifie également que tu utilises l'adresse Web (URL) correcte pour la propriété 'href'.

La partie d'une adresse Web située après le nom de domaine (comme 'projects.raspberrypi.org') est sensible à la casse, tu dois donc t'assurer que les lettres majuscules correspondent.

Cet exemple utilise le code HTML correct pour créer un lien vers une page Web qui s'ouvre dans un nouvel onglet de navigateur :

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<a href="https://projects.raspberrypi.org/en/raspberrypi/web-intro" target="_blank">Crée une page Web comme celle-ci !</a>

\--- /code ---
