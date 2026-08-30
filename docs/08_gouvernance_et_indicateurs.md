# Gouvernance proportionnée et indicateurs

> Documentation du cadre **ReUse-CH** · [⬅ Retour à l'index](README.md)

## Une gouvernance par fonction, pas par taille de liste

La gouvernance numérique n'est pas une liste de dispositifs à cocher : c'est un petit nombre de **fonctions** que toute administration doit assurer, chacune avec une intensité proportionnée à sa taille, ses moyens et ses risques. Le tableau ci-dessous décline ces fonctions selon les trois niveaux d'adoption du cadre. Chaque administration lit **sa colonne** : les autres décrivent d'où elle vient ou vers où elle peut aller, pas ce qui lui manque.

### Si vous êtes une petite administration

La colonne « Démarrer » **est** votre gouvernance complète. Rien d'autre n'est attendu de vous : une personne référente, un registre tenu, le réflexe checklist avant tout achat, des exigences minimales de sécurité et la réversibilité dans les contrats importants. Ce sont les [cinq actions minimales](05_adoption_progressive.md) du cadre, formulées comme fonctions durables plutôt que comme actions ponctuelles. Une commune qui assure cela gouverne réellement son numérique, quoi qu'en disent les référentiels épais.

### Le tableau des fonctions

| Fonction | Démarrer | Structurer | Mutualiser et partager |
|---|---|---|---|
| **Responsabilité** | Une personne référente pour le numérique, même à temps très partiel | Rôle formalisé avec suppléance ; contacts désignés pour la sécurité et la protection des données | Instance de gouvernance associant direction, métiers et informatique |
| **Décision d'achat et de projet** | Le réflexe [checklist](../outils/checklist_projet.md) avant tout nouvel outil ou contrat | Processus de validation documenté ; critères communs pour achats, renouvellements et remplacements | Portefeuille de projets avec arbitrages ; grille valeur/coût/risque/durabilité |
| **Visibilité** | Le [registre](../outils/registre_applications_fournisseurs.md) applications, fournisseurs et contrats critiques, tenu par une personne | Registre enrichi (risques, échéances, coûts), revu au moins une fois par an | Cartographie complète incluant dépendances, flux de données et API |
| **Sécurité et risques** | Exigences minimales de sécurité et de protection des données sur toute nouvelle solution | Suivi des risques numériques ; processus de validation des changements réalisés par les prestataires | Cybergouvernance continue ; analyse de risques systématique ; exercices de continuité |
| **Contrats et prestataires** | Réversibilité et documentation exigées dans les contrats importants | Exigences fournisseurs formalisées ; documentation minimale exigée pour chaque solution critique | Référentiel d'exigences publié et mutualisé ; réversibilité testée, pas seulement contractuelle |
| **Amélioration et partage** | Noter ce qui a marché ou pas à la fin de chaque projet | Retours d'expérience systématiques ; quelques indicateurs suivis | RETEX publiés ; contribution active aux communs (voir ci-dessous) |

### Si vous êtes une grande administration

ReUse-CH est pour vous un **plancher, pas un plafond**. Pour la profondeur (contrôles, processus, audit), appuyez-vous sur vos référentiels établis : COBIT, ISO 27001, HERMES, vos cadres cantonaux. Ce que ReUse-CH vous apporte, c'est ce que ces référentiels ne couvrent pas : la dimension **réutilisation, mutualisation et contribution aux communs**, avec une responsabilité particulière. Une grande administration qui mutualise entraîne dix petites derrière elle ; une qui garde tout pour elle les condamne à racheter.

Au niveau « Mutualiser et partager », le cadre attend donc des engagements concrets :

- **publier par défaut en open source** les développements financés par des fonds publics, en appliquant volontairement le principe que la LMETA (art. 9) impose à la Confédération ;
- **contribuer en retour** aux solutions libres utilisées : code, financement, gouvernance ou retours d'expérience ;
- **publier un catalogue d'API** et documenter les interfaces réutilisables, sur I14Y ou une plateforme équivalente, en exigeant les standards eCH de ses fournisseurs ;
- **ouvrir ses données** publiques non sensibles sur opendata.swiss, avec des métadonnées DCAT-AP-CH ;
- **penser mutualisation dès l'appel d'offres** : lorsque le droit des marchés publics le permet, prévoir l'ouverture des contrats-cadres à d'autres collectivités, ou passer par des structures communes comme eOperations Suisse ;
- **tester réellement la réversibilité** de ses systèmes critiques (export, restauration), au lieu de s'en remettre à la clause contractuelle ;
- **doter chaque solution partagée qu'elle opère d'une gouvernance de maintenance** : propriétaire fonctionnel, mainteneur, règles de contribution et de financement ;
- **publier son référentiel d'exigences fournisseurs et ses retours d'expérience**, pour que les administrations plus petites n'aient pas à les réinventer.

## Indicateurs et preuves

ReUse-CH encourage une logique de preuve simple. Chaque principe devrait pouvoir être associé à une preuve concrète, par exemple :

- décision documentée ;
- indicateur suivi ;
- test utilisateur réalisé ;
- standard utilisé ;
- donnée publiée ;
- API documentée ;
- clause contractuelle intégrée ;
- analyse de risque effectuée ;
- mesure de réduction d'impact ;
- solution réutilisée ;
- retour d'expérience partagé ;
- exigence fournisseur vérifiée ;
- plan de réversibilité établi ;
- documentation de configuration fournie.

Les indicateurs doivent rester utiles et limités en nombre. Il vaut mieux suivre quelques indicateurs réellement utilisés pour décider et améliorer, plutôt que de multiplier les mesures sans effet sur les pratiques.

### Le kit de départ : trois mesures

Pour une administration qui démarre, trois mesures suffisent, toutes tirées d'outils déjà en place :

1. **le coût récurrent annuel total** des licences et abonnements (il sort directement du registre des contrats) ;
2. **la part des contrats critiques** comportant une clause de portabilité et de réversibilité ;
3. **un signal de satisfaction** des usagers ou des collaborateurs, même artisanal (quelques questions une fois par an valent mieux qu'aucune mesure).

### Le menu complet, par pilier

Les listes suivantes sont un **menu** pour les niveaux Structurer et Mutualiser, pas un programme : choisissez-y ce qui éclaire réellement vos décisions. Un tableau de bord resserré avec seuils d'action est prévu à la [feuille de route](../roadmap/outils.md).

#### Sociétal

- taux de satisfaction utilisateur ;
- nombre de tests utilisateurs réalisés ;
- conformité aux exigences d'accessibilité ;
- nombre de prestations disposant d'une alternative non numérique ;
- nombre de jeux de données publiques ouverts ;
- nombre de traitements documentés.

#### Économique

- part des projets ayant vérifié la réutilisation avant acquisition ;
- nombre de solutions mutualisées ;
- coûts récurrents des licences et abonnements ;
- coûts évités par réutilisation ;
- nombre de fournisseurs et de contrats numériques critiques documentés ;
- part des marchés intégrant des clauses de portabilité et réversibilité ;
- part des solutions disposant d'un plan de réversibilité ;
- part des fournisseurs évalués selon des critères ReUse-CH ;
- nombre de développements spécifiques documentés et réutilisables ;
- dépendances fournisseurs critiques identifiées ;
- dette technique identifiée.

#### Environnemental

- durée moyenne d'usage des équipements ;
- part du matériel réemployé ou reconditionné ;
- volume de stockage ;
- consommation cloud ou infrastructure ;
- part des achats intégrant des critères de cycle de vie ;
- nombre de services numériques ayant fait l'objet d'une analyse de sobriété ;
- bilan GES ou estimation CO₂eq lorsque disponible.

---

*ReUse-CH – Cadre volontaire pour une transformation numérique Responsable, Innovante et Mutualisée – Licence [CC BY-SA 4.0](../LICENSE.md)*
