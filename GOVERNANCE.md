# Gouvernance du projet ReUse-CH

Ce document décrit comment le cadre ReUse-CH lui-même est maintenu et évolue : un cadre de gouvernance se doit de documenter la sienne.

## Origine et remerciements

La version de base du cadre a bénéficié de la participation active et de l'expérience de **Milena Taboada**, **David Jeanmonod** et **Andrea Naef**, dans le cadre de la [Swiss IT Sustainability Community of Practice](https://www.linkedin.com/company/swiss-it-sustainability-community-of-practice/). Qu'ils et elles en soient remerciés : un cadre de réutilisation ne pouvait décemment pas naître d'une seule personne.

## Rôles

- **Mainteneur** : [@barthelemyr](https://github.com/barthelemyr). Il arbitre les évolutions, fusionne les pull requests, publie les versions.
- **Contributeur·rice·s** : toute personne proposant issues, pull requests, cas d'usage ou relectures.
- **Communauté** : la [Swiss IT Sustainability Community of Practice](https://www.linkedin.com/company/swiss-it-sustainability-community-of-practice/), espace d'échange et de diffusion.

Ce modèle volontairement simple n'est pas figé : suivant le développement et l'adoption du cadre, sa gouvernance pourra évoluer, par exemple vers des co-mainteneur·euse·s, un comité éditorial, ou une structure plus formelle si des administrations ou des institutions s'engagent durablement. Toute évolution de la gouvernance sera elle-même discutée en issue et tracée dans le CHANGELOG.

## Processus de décision

- **Corrections et améliorations mineures** (typos, clarifications, liens) : pull request, fusion par le mainteneur.
- **Nouveaux outils ou cas d'usage** : issue de proposition recommandée avant la pull request, pour valider la pertinence et éviter le travail en double.
- **Évolutions structurantes** (modification des axes, réflexes, piliers ou niveaux d'adoption) : en phase 0.x, une simple issue de discussion suffit, puisque c'est précisément l'objet de la co-construction ; les décisions sont prises au consensus autant que possible, motivées par le mainteneur sinon. À partir de la v1.0, ces évolutions passeront par une issue « RFC » ouverte au moins 30 jours.

## Versions du cadre

Le cadre est actuellement en **phase de co-construction** (versions 0.x) :

- **Versions 0.x** : base de travail évolutive. Tout est discutable, y compris la structure (axes, réflexes, cycle, niveaux d'adoption). Chaque itération notable incrémente la version mineure (0.2.0, 0.3.0…). Les propositions structurantes sont bienvenues via issues et discussions, sans le formalisme RFC complet.
- **Version 1.0.0** : sera publiée lorsque la structure aura été **stabilisée avec la communauté** et validée par des retours d'usage réels d'administrations. C'est la version 1.0 que les administrations pourront citer comme référence stable.
- **Après la 1.0** : versionnage sémantique classique (MAJEURE : changement de structure ; MINEURE : nouveaux outils et enrichissements compatibles ; CORRECTIVE : corrections sans changement de fond), avec processus RFC pour les évolutions structurantes.

Chaque version est publiée comme *release* GitHub et consignée dans le [CHANGELOG](CHANGELOG.md). En phase 0.x, les outils sont déjà utilisables, en sachant que le cadre reste évolutif.
