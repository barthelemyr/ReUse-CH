# Backlog de co-construction ReUse-CH

Ce document liste les questions ouvertes du cadre identifiées lors de la revue de cohérence de la v0.1. Chaque entrée est conçue comme une **issue GitHub prête à créer** : copiez le titre et le corps, ajoutez les étiquettes indiquées. Ces sujets sont volontairement laissés ouverts : ils relèvent de choix que la communauté doit faire ensemble, pas d'une correction unilatérale.

---

## B1. Matrice de passage entre les cinq réflexes et les cinq axes

**Titre :** `[Co-construction] Relier les cinq réflexes et les cinq axes : proposition de matrice de passage`
**Étiquettes :** `co-construction`, `documentation`

**Corps :**
La checklist avant-projet est structurée par réflexes, le diagnostic de maturité par axes. Les deux grilles de lecture cohabitent sans table de correspondance : un lecteur ne sait pas si les réflexes sont une vue simplifiée des axes ou une dimension transversale. Proposition : élaborer une matrice réflexes × axes d'une demi-page, à intégrer dans docs/02 ou docs/03. Toute proposition de correspondance est bienvenue en commentaire.

---

## B2. Arbitrer entre « Réutiliser avant tout » et « Concevoir pour l'utilisateur »

**Titre :** `[Co-construction] Quand une solution réutilisée sert moins bien les usagers : comment arbitrer ?`
**Étiquettes :** `co-construction`, `outil`

**Corps :**
Une solution reprise d'une autre collectivité peut être moins adaptée aux usagers locaux qu'une solution sur mesure. Cette tension entre les réflexes 1 et 4 est la plus fréquente en pratique et le cadre ne propose pas de méthode d'arbitrage. À intégrer dans la future grille d'arbitrage valeur/coût/risque/durabilité (voir roadmap). Retours de terrain particulièrement bienvenus : dans quels cas avez-vous renoncé à réutiliser, et pourquoi ?

---

## B3. Mutualiser le pilotage des prestataires

**Titre :** `[Co-construction] Comment des petites communes peuvent-elles piloter ensemble leurs prestataires ?`
**Étiquettes :** `co-construction`, `prestataires`

**Corps :**
Le cadre demande aux administrations de développer leur capacité à piloter et challenger les fournisseurs, tout en reconnaissant que les petites communes n'en ont pas les moyens individuellement. La réponse logique est la mutualisation du pilotage, mais ses formes concrètes restent à définir : groupements de communes utilisant le même fournisseur, appui cantonal, recours à eOperations Suisse, communautés de pratique par produit ? Expériences existantes et propositions bienvenues.

---

## B4. Mesurer la valeur publique

**Titre :** `[Co-construction] Quel indicateur simple pour la « valeur publique créée » ?`
**Étiquettes :** `co-construction`, `indicateurs`

**Corps :**
Le pilier économique vise à « maximiser la valeur publique par franc investi » et le réflexe Mesurer mentionne la « valeur publique créée », mais aucun indicateur proposé ne la mesure : les indicateurs économiques actuels comptent des coûts et des éléments de conformité. Faut-il un proxy (satisfaction × taux d'utilisation, nombre de prestations rendues) ou assumer que le cadre mesure les coûts évités ? Propositions d'indicateurs praticables par une petite commune bienvenues.

---

## B5. Position du cadre sur Microsoft 365 et le cloud public

**Titre :** `[Co-construction] Souveraineté numérique en pratique : quelle position sur M365 et le cloud public ?`
**Étiquettes :** `co-construction`, `souveraineté`, `sensible`

**Corps :**
Le cadre promeut des « infrastructures souveraines » et la souveraineté numérique figure parmi les priorités de la stratégie Suisse numérique 2026. Or l'arbitrage de souveraineté que la plupart des communes vivent concrètement concerne Microsoft 365 et le cloud public américain. Le cadre doit-il prendre position, proposer une grille de décision (types de données, préavis des préposés à la protection des données, alternatives), ou rester neutre ? Sujet sensible : tous les points de vue argumentés sont bienvenus, y compris ceux des prestataires.

---

## B6. Reformulation du vocabulaire prescriptif des axes

**Titre :** `[Amélioration] Passe de reformulation des axes : distinguer recommandation et exigence`
**Étiquettes :** `documentation`, `good first issue`

**Corps :**
Une note de lecture a été ajoutée en tête des axes (v0.1) pour préciser que les formulations prescriptives (« garantir », « exiger ») sont des recommandations, sauf obligation légale. Une passe de reformulation plus fine reste souhaitable : distinguer systématiquement ce qui relève du droit (LPD, LHand, marchés publics), ce que le cadre recommande aux administrations, et ce que les administrations peuvent exiger de leurs prestataires. Bonne première contribution pour une personne à l'aise avec la rédaction.

---

## B7. Faire des niveaux d'adoption la structure éditoriale principale

**Titre :** `[Co-construction] Restructurer le cadre autour de trois statuts : socle indispensable, pratiques recommandées, capacités avancées`
**Étiquettes :** `co-construction`, `documentation`, `structurant`

**Corps :**
Une revue externe de la v0.1 relève que le périmètre du cadre est très large et que tous les éléments semblent avoir le même statut, ce qui le rend difficile à expliquer et à piloter. Les niveaux d'adoption (Démarrer / Structurer / Mutualiser) font déjà cette distinction de fait ; la proposition est d'en faire la structure éditoriale principale : chaque exigence, outil et pratique serait explicitement marqué « socle », « recommandé » ou « avancé ». C'est une réécriture structurante : à discuter avant d'engager le travail, idéalement pour la v0.2 ou la v1.0. Un premier pilote de cette approche a été appliqué au chapitre gouvernance (docs/08 : fonctions × niveaux d'adoption) ; l'atelier de validation permettra de juger sur pièce avant de généraliser.

---

## B8. Gouvernance de maintenance des solutions partagées (« produit commun »)

**Titre :** `[Co-construction] Qui maintient, anime et finance ce qui est partagé ?`
**Étiquettes :** `co-construction`, `mutualisation`

**Corps :**
Le cadre appelle au partage et à la mutualisation, mais précise peu qui anime les communautés, qui maintient les composants partagés, qui finance leur évolution et sous quelles règles de contribution. Sans gouvernance de maintenance, la réutilisation risque de se limiter à la copie ponctuelle de documents. Un modèle léger de « produit commun » est proposé à la roadmap (propriétaire fonctionnel, mainteneur technique, communauté utilisatrice, backlog partagé, versionnage, financement) : cette issue recueille les retours d'expérience, notamment de projets comme Geocity, pour le construire sur du vécu plutôt que sur la théorie.

---

## Suivi

| # | Sujet | Origine | Statut |
|---|---|---|---|
| B1 | Matrice réflexes × axes | Revue de cohérence v0.1, pt 4 | ⏳ Issue à créer |
| B2 | Arbitrage réutilisation / usager | Revue de cohérence v0.1, pt 5 | ⏳ Issue à créer |
| B3 | Pilotage mutualisé des prestataires | Revue de cohérence v0.1, pt 6 | ⏳ Issue à créer |
| B4 | Indicateur de valeur publique | Revue de cohérence v0.1, pt 8 | ⏳ Issue à créer |
| B5 | Position M365 / cloud public | Revue de cohérence v0.1, pt 15 | ⏳ Issue à créer |
| B6 | Vocabulaire prescriptif des axes | Revue de cohérence v0.1, pt 1 | ⏳ Issue à créer |
| B7 | Structure éditoriale socle / recommandé / avancé | Revue externe v0.1 | 🚧 Pilote appliqué à docs/08 ; issue à créer pour la généralisation |
| B8 | Gouvernance de maintenance du partagé (« produit commun ») | Revue externe v0.1 | ⏳ Issue à créer |

---

*ReUse-CH – Cadre volontaire pour une transformation numérique Responsable, Innovante et Mutualisée – Licence CC BY-SA 4.0*
