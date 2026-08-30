# Changelog

Toutes les évolutions notables du cadre ReUse-CH sont consignées ici. Le format s'inspire de Keep a Changelog et le versionnage est décrit dans [GOVERNANCE.md](GOVERNANCE.md).

## [0.1.0] – 2026-08-30

Première version de travail du cadre, publiée comme **base de co-construction**. La structure (axes, réflexes, cycle, outils) est ouverte à la discussion et évoluera avec les retours de la communauté jusqu'à une v1.0 stabilisée collectivement.

### Renommé
- Le cadre adopte le nom **ReUse-CH** (anciennement « ReUse IT ») afin d'éviter toute confusion avec re-useIT, plateforme commerciale suisse de revente de matériel informatique, et d'ancrer le périmètre national. Le cycle R-E-U-S-E et le contenu du cadre sont inchangés.

### Ajouté
- **Domaine officiel `reuse-ch.ch`** : fichier `docs/CNAME` pour GitHub Pages, toutes les références à l'outil d'état des lieux basculées vers https://reuse-ch.ch/, instructions DNS et HTTPS dans le guide de publication.
- **GOVERNANCE.md** : section « Origine et remerciements » (Milena Taboada, David Jeanmonod, Andrea Naef, dans le cadre de la Swiss IT Sustainability Community of Practice) et clause d'évolution de la gouvernance selon le développement et l'adoption du cadre.
- **Outil web d'état des lieux et de suivi** (v0.5, FR/DE) intégré au dépôt : déployé via `docs/index.html` (GitHub Pages), sources dans `site/`. Fonctionne sans base de données ni serveur ; le suivi s'exporte dans un fichier appartenant à l'administration.
- **Articulation avec l'ISIT-CH** : la charte, le label, les formations Numérique Responsable et les outils de mesure d'empreinte de l'institut sont référencés en détail (docs/10, références), cités dans les axes 2 et 3, ajoutés au tableau d'articulation (docs/01) et posés comme socle des futurs outils d'écoconception et de formation (roadmap). ReUse-CH renvoie à ces instruments pour le volet numérique responsable plutôt que de les dupliquer.
- **Kit d'atelier de validation** (`atelier/`) : déroulé animateur minuté pour une demi-journée en présentiel avec des praticiens communaux, feuille de capture des retours transcriptible en issues GitHub, kit participant d'une page.
- Suite à une revue externe de la v0.1 : règle de spécification des outils (décision servie, responsable, fréquence de revue) dans la roadmap ; trois nouveaux outils planifiés (tableau de bord resserré à seuils, grille de classification des risques IA, modèle de « produit commun ») ; propriétaire et cadence de revue ajoutés au registre ; entrées B7 et B8 au backlog de co-construction.
- **Références légales et services de base nationaux** : LMETA/EMBAG, LMP/AIMP, LSI (annonce des cyberattaques à l'OFCS), LHand, AGOV, e-ID étatique, service national des adresses, I14Y, opendata.swiss et eOperations Suisse, référencés dans `docs/10` (références) et intégrés aux axes, au réflexe « Réutiliser avant tout », aux niveaux d'adoption et au tableau d'articulation.
- **Backlog de co-construction** (`roadmap/backlog.md`) : issues prêtes à créer sur les questions ouvertes du cadre.
- Clarifications de positionnement : distinction entre socle légal et surcroît volontaire, complémentarité avec les offres cantonales aux communes, cœur de cible communal, note de lecture sur le vocabulaire prescriptif des axes, articulation entre gouvernance minimale et actions minimales, niveaux d'adoption définis par les pratiques plutôt que par la taille.
- Section **« Positionnement »** (README FR/DE et docs/01) : cadre **volontaire**, **complémentaire** aux stratégies fédérales (ANS) et cantonales, **flexible et proportionné**, pour une **transformation numérique responsable**, avec schéma d'insertion institutionnelle (Mermaid).
- **Versions allemandes** du README (`README.de.md`) et de la checklist avant-projet (`outils/checklist_projet.de.md`), avec sélecteurs de langue et bandeau « relecture bienvenue ». Politique linguistique documentée dans `CONTRIBUTING.md` : le français fait foi, traductions en fichiers suffixés, contributions bienvenues en FR/DE/IT/EN.
- **Checklist interactive** (`outils/checklist_projet.html`) : mini-site HTML autonome, sans cookie ni script tiers.
- **Checklist ReUse-CH avant-projet** (`outils/checklist_projet.md`) : versions express (10 questions) et complète, avec fiche de décision.
- **Checklist interactive** (`outils/checklist_projet.html`) : mini-site autonome en un fichier, responsive et accessible, conforme aux principes Web B (aucun cookie, aucun script ni police tiers, aucune collecte de données, fonctionne hors ligne) ; fiche de décision remplie en direct et imprimable.
- **Registre des applications, fournisseurs et contrats critiques** (`outils/registre_applications_fournisseurs.md`).
- Documentation structurée dans `docs/` (11 documents thématiques + index), issue de l'ancien README monolithique.
- `GOVERNANCE.md`, `CODE_OF_CONDUCT.md`, `CHANGELOG.md`.

### Modifié
- **Références (docs/10) refondues** : chaque référence pointe vers sa source officielle (URL vérifiées : Fedlex pour la LPD et la LMETA, digital.swiss, ANS, AGOV, I14Y, opendata.swiss, eOperations, eCH, HERMES, WCAG, ISO, ISACA, ISIT-CH) avec une ligne descriptive ; reclassement (la LPD rejoint les bases légales, la NCS les stratégies) ; FinOps et Green IT retirés (couverts par le tableau d'articulation et l'ISIT) ; le nuage de « thèmes associés » devient un index thématique liant chaque thème au chapitre qui le traite ; phrases de synthèse hiérarchisées avec définition de référence alignée sur le positionnement ; principe directeur corrigé (bug de rendu Markdown), doté d'un renvoi depuis les réflexes (docs/02) et ajouté au matériel d'atelier comme affiche.
- **Dissolution de « Utiliser le cadre » (ancien docs/10)** : le tableau d'articulation avec les cadres et instruments existants est promu dans docs/01, à la suite du positionnement ; les mises en garde encore utiles de « Ce que ReUse-CH n'est pas » y sont condensées en un paragraphe ; les listes « Utiliser le cadre », couvertes depuis par le README et docs/05, sont supprimées. Les références passent de docs/11 à docs/10 ; la documentation compte désormais 10 fichiers.
- **Gouvernance (docs/08) restructurée en gouvernance proportionnée** : tableau des fonctions × niveaux d'adoption (la colonne « Démarrer » est la gouvernance complète d'une petite administration et correspond aux cinq actions minimales), paragraphe « plancher, pas plafond » avec huit engagements concrets du niveau « Mutualiser » pour les grandes administrations (open source par défaut selon l'esprit de la LMETA, contribution aux communs, catalogue d'API, open data, mutualisation dès l'appel d'offres, réversibilité testée, gouvernance de maintenance, publication des exigences et RETEX), kit de départ de trois indicateurs et listes par pilier reformulées en menu. Ce chapitre sert de pilote au backlog B7.
- **Boîte à outils (docs/06) restructurée** en vitrine utilisateur : bandeau de transparence (outils utilisables aujourd'hui vs intentions), sept outils disponibles décrits en deux lignes (ce que c'est, ce que ça apporte), intentions regroupées par famille en une ligne chacune, renvoi à la feuille de route comme source des priorités et statuts, et lien réciproque depuis la roadmap.
- **README (FR et DE) restructuré en parcours** : pitch, positionnement, cinq réflexes, « comment ça se déroule » en trois temps citant le cycle R-E-U-S-E, appel à l'action unique vers l'outil d'état des lieux, liens secondaires. Les tables des actions, documents et outils redescendent dans docs/ et la roadmap. Articulation explicite entre l'outil (suivi continu) et le diagnostic (évaluation ponctuelle scorée). Flux « bonnes pratiques partagées » ajouté vers l'ANS/DVS dans les schémas de positionnement.
- **Diagnostic de maturité** (`outils/diagnostic_maturite.md`) : fusion du questionnaire et de la grille, réalignement sur les cinq axes ReUse-CH, ajout de la réutilisation/mutualisation au cœur des questions, système de score et articulation avec les niveaux d'adoption (Démarrer / Structurer / Mutualiser).
- **README** : version courte orientée découverte et premiers pas.
- `CONTRIBUTE.md` renommé en `CONTRIBUTING.md`, corrigé (cinq axes, chemins réels) et enrichi.
- `LICENSE` : texte officiel CC BY-SA 4.0 (détection automatique par GitHub) ; le résumé en français est déplacé dans `LICENSE.md`.
- Feuille de route (`roadmap/outils.md`) : ajout des priorités et statuts.

### Supprimé
- `outils/questionnaire_maturite.md` et `outils/grille_evaluation_maturite.md`, remplacés par le diagnostic fusionné.
