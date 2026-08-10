# Le Piège Référendaire — maquette de direction artistique

Maquette du microsite **Le Piège Référendaire**, dans la direction **« Kraft »** retenue.

**Démo :** https://paulalexandrerichard-code.github.io/piege-referendaire-maquettes/

## La direction retenue

Chemise kraft, feuilles ivoire posées sur fond charbon, perforations de marge, tampons rouges partiellement superposés, parallaxe de couches documentaires. Le visiteur n'a pas l'impression de faire défiler une page, mais d'ouvrir un dossier et d'en consulter les pièces.

Cinq directions ont été explorées au départ — Kraft, Microfilm, Bordereau, Table d'enquête, Caviardage. Les quatre écartées restent consultables dans l'historique git (`git show 4bd29ae`).

## Ce que contient la maquette

Hero, note de synthèse, index des quatre fiches, fiches 01 et 02 avec accordéon fonctionnel, fiche 04 traitée distinctement comme sortie du dossier, conclusion et emplacements de sources.

## Portée

Ceci est une **maquette de direction artistique**, pas le site final.

Le texte visible provient du contenu maître du projet. Les fiches détaillées n'existant qu'à l'état de plan, les accordéons affichent leur ossature réelle avec les zones de rédaction marquées « À RÉDIGER » — **aucun fait n'a été inventé**, et aucune source n'est encore versée.

## Technique

HTML + CSS autonomes, environ 30 lignes de JavaScript, sans dépendance autre que Google Fonts. Accordéons avec `aria-expanded` / `aria-controls`, focus visible, `prefers-reduced-motion` respecté.

Les pages portent un `meta robots noindex` et le dépôt un `robots.txt` restrictif : la démo est accessible par lien, mais n'est pas indexée par les moteurs de recherche.
