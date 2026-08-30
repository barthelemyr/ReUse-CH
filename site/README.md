# Outil d'état des lieux et de suivi – sources

Ce dossier contient les sources de l'outil web « ReUse-CH – État des lieux & suivi » (v0.5) :

- `index_template.html` : gabarit source de la page ;
- `reuse-it.scss` : feuille de style source (variables Bootstrap personnalisées) ;
- `index.html` : fichier construit, autonome, identique à celui déployé dans `docs/index.html` et servi par GitHub Pages.

L'outil fonctionne entièrement dans le navigateur : aucune base de données, aucun serveur, aucune donnée transmise. Le suivi s'exporte dans un fichier JSON qui appartient à l'administration.

Pour modifier l'outil : éditer les sources, reconstruire `index.html`, puis copier le résultat dans `docs/index.html`.
