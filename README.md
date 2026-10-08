# UltraStar Prompter

Lecteur de karaoké pour le navigateur, centré sur l'affichage : il lit un dossier de chansons au format [UltraStar](https://usdx.eu/format/) et fait défiler les paroles en rythme. Pas de micro, pas de score.

## Utilisation

1. Ouvre `index.html` dans Chrome, Edge ou Firefox (aucune installation, aucun serveur).
2. Clique sur « Choisir le dossier songs » et sélectionne ton dossier de chansons, par exemple `C:\Users\Admin\Documents\Ultrastar\songs`. Tu peux aussi le glisser sur la page.
3. Choisis une chanson.

Les fichiers ne quittent pas ta machine. Chaque chanson est un dossier `Artiste - Titre` contenant un `.txt` UltraStar, l'audio et éventuellement une pochette, un fond et un clip.

## Affichage

- Ligne en cours colorée syllabe par syllabe, ligne suivante en dessous, transition douce entre les lignes.
- Barres de notes de la ligne (hauteurs lues dans le `.txt`), notes dorées en jaune.
- Compte à rebours avant chaque reprise après un silence.
- Duos (P1/P2) sur deux pistes.
- Pochette, fond ou clip (MP4/WebM) en arrière-plan.

## Raccourcis

| Touche | Action |
| --- | --- |
| Espace | Lecture / pause |
| ← / → | Reculer / avancer de 5 s |
| N | Chanson suivante |
| F | Plein écran |
| Échap | Retour à la liste |

Les boutons − / + décalent les paroles par pas de 50 ms.

## Limites

- Les clips `.avi` / `.divx` ne sont pas lisibles par les navigateurs : la pochette les remplace.
- Les polices viennent de Google Fonts ; hors ligne, une police système prend le relais.

## Licence

MIT
