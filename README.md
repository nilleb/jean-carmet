# Soirées au Jean Carmet

Page statique listant les séances et spectacles à **19h30 ou plus tard** du
[Théâtre Cinéma Jean Carmet](https://www.theatre-cinema-jean-carmet.fr/) à Mornant.

Chaque titre pointe vers sa fiche AlloCiné ; le bouton « + Agenda » crée l'événement
dans Google Agenda avec l'horaire, la durée réelle du film et le lieu.

→ **https://nilleb.github.io/jean-carmet/**

## D'où ça vient

`index.html` est généré, jamais édité à la main. La source vit dans le vault :
`~/dev/brain/.scripts/jean-carmet/` (données `program.json` + `template.html` +
`render.py`), rafraîchie chaque dimanche matin par la skill `/jean-carmet-weekly`
(launchd `co.nillebco.jean-carmet-weekly`), qui republie ici et poste le lien sur Signal.
