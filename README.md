# Le Piège Référendaire — maquettes de conception

Cinq directions visuelles pour le microsite **Le Piège Référendaire**, présentées dans une visionneuse à onglets.

**Démo :** https://paulalexandrerichard-code.github.io/piege-referendaire-maquettes/

## Les cinq directions

| # | Direction | Parti pris |
|---|---|---|
| 01 | Kraft | Chemise kraft, feuilles ivoire sur charbon, perforations, tampons, parallaxe de couches |
| 02 | Microfilm | Noir et blanc haut contraste, perforations de pellicule, index en table de bobine |
| 03 | Bordereau | Papier clair, grille technique, numérotation décimale, index latéral sticky, bleu institutionnel |
| 04 | Table d'enquête | Documents étalés, onglets de chemise en navigation, cartes pivotées, annotation manuscrite |
| 05 | Caviardage | Typographie monumentale, barres de caviardage comme rythme, fiche 04 « déclassifiée » |

## Utilisation de la visionneuse

- Onglets, ou touches `←` `→` et `1`–`5`
- Sélecteur de largeur : pleine / 820 px / 400 px pour comparer le rendu mobile
- « Ouvrir seule ↗ » affiche une maquette en plein écran
- Lien direct vers une direction : `#kraft`, `#microfilm`, `#bordereau`, `#table`, `#caviardage`

## Portée

Ce sont des **maquettes de direction artistique**, pas le site final. Chacune contient : hero, note de synthèse, index des quatre fiches, fiches 01 et 02 avec accordéon fonctionnel, fiche 04 traitée distinctement, conclusion et emplacements de sources.

Le texte visible provient du contenu maître du projet. Les fiches détaillées n'existant qu'à l'état de plan, les accordéons affichent leur ossature réelle avec les zones de rédaction marquées « À RÉDIGER » — **aucun fait n'a été inventé**, et aucune source n'est encore versée.

## Technique

HTML + CSS autonomes, environ 30 lignes de JavaScript par page, sans dépendance autre que Google Fonts. Accordéons avec `aria-expanded` / `aria-controls`, focus visible, `prefers-reduced-motion` respecté.

Les pages portent un `meta robots noindex` et le dépôt un `robots.txt` restrictif : la démo est accessible par lien, mais n'est pas indexée par les moteurs de recherche.
