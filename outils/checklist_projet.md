# Checklist ReUse-CH – Avant tout nouveau projet numérique

> **Français** · [Deutsch](checklist_projet.de.md)
>
> Outil du cadre **ReUse-CH** · [Documentation](../docs/README.md) · Licence [CC BY-SA 4.0](../LICENSE.md)

## Objectif

Vérifier, **avant** de lancer un projet, un achat, un développement ou un renouvellement de contrat numérique, que les cinq réflexes ReUse-CH ont été pris en compte : réutiliser, mesurer, partager, concevoir pour l'utilisateur, sécuriser par défaut.

## Quand l'utiliser

- Nouveau logiciel, abonnement ou service en ligne (même « gratuit ») ;
- nouveau développement ou configuration importante par un prestataire ;
- renouvellement ou remplacement d'une solution existante ;
- nouveau traitement de données ou nouvelle prestation en ligne.

## Proportionnalité

Deux niveaux d'utilisation, selon le principe *just enough, just in time, just for the risk* :

| Situation | Version à utiliser |
|---|---|
| Petit projet, données non sensibles, faible coût, faible dépendance | **Version express** (10 questions, ~15 min) |
| Projet critique, données personnelles ou sensibles, contrat structurant, forte dépendance fournisseur | **Version complète** (sections A à G) |

---

## Version express (10 questions)

À remplir par la personne responsable du projet. Toute réponse « Non » sans justification devrait faire l'objet d'une discussion avant décision.

| # | Question | Oui | Non | N/A |
|---|---|---|---|---|
| 1 | Le besoin est-il réel, exprimé par les utilisateurs et non couvert par un outil existant en interne ? | ☐ | ☐ | ☐ |
| 2 | Avons-nous vérifié si une autre commune, le canton, la Confédération ou une plateforme mutualisée propose déjà une solution réutilisable ? | ☐ | ☐ | ☐ |
| 3 | Avons-nous vérifié l'existence d'une solution open source pertinente ? | ☐ | ☐ | ☐ |
| 4 | Connaissons-nous le coût complet (acquisition, exploitation, maintenance, formation, sortie) et pas seulement le prix d'achat ? | ☐ | ☐ | ☐ |
| 5 | Les données traitées, leur sensibilité et leur lieu d'hébergement sont-ils identifiés ? | ☐ | ☐ | ☐ |
| 6 | Les exigences minimales de sécurité et de protection des données (LPD) sont-elles couvertes ? | ☐ | ☐ | ☐ |
| 7 | Pourrons-nous récupérer nos données et changer de solution si nécessaire (réversibilité) ? | ☐ | ☐ | ☐ |
| 8 | La solution sera-t-elle accessible (eCH-0059 / WCAG) et utilisable par les publics concernés ? | ☐ | ☐ | ☐ |
| 9 | La documentation minimale (configuration, interfaces, responsabilités) est-elle prévue ? | ☐ | ☐ | ☐ |
| 10 | La décision (réutiliser / adapter / acheter / développer) est-elle documentée avec ses raisons ? | ☐ | ☐ | ☐ |

**Décision :** ☐ Réutiliser ☐ Adapter ☐ Acheter ☐ Développer ☐ Abandonner / reporter

**Justification (3 lignes suffisent) :**

---

## Version complète

### A. Utilité et cadrage

*Avant de numériser, questionner l'utilité.*

- [ ] Le besoin est décrit du point de vue des usagers ou des collaborateurs (pas seulement de la technique).
- [ ] La base légale et l'intérêt public sont identifiés si le projet touche des prestations ou des données personnelles.
- [ ] La solution est proportionnée au besoin (pas de sur-dimensionnement).
- [ ] Une alternative non numérique est maintenue si la prestation s'adresse à la population.
- [ ] Le service ou la personne responsable du projet est désigné.

### B. Réutiliser avant tout

*Avant d'acheter, chercher à réutiliser.*

- [ ] Vérification interne : une solution ou un contrat existant peut-il couvrir le besoin ?
- [ ] Vérification externe : une autre commune, le canton, la Confédération ou une association intercommunale dispose-t-elle d'une solution réutilisable ?
- [ ] Vérification des plateformes et services mutualisés existants.
- [ ] Vérification des solutions open source pertinentes (p. ex. utilisées par d'autres collectivités suisses).
- [ ] Vérification auprès du fournisseur pressenti : existe-t-il une configuration, une extension ou une interface déjà utilisée par d'autres administrations ?
- [ ] Les standards applicables (eCH, DCAT-AP-CH, formats ouverts) sont identifiés.
- [ ] La décision **réutiliser / adapter / acheter / développer** est documentée, avec les options écartées et leurs raisons.

### C. Mesurer pour améliorer

- [ ] 3 à 5 indicateurs simples sont choisis (p. ex. coût annuel complet, satisfaction, taux d'utilisation, incidents).
- [ ] La situation de départ (baseline) est notée pour pouvoir comparer.
- [ ] Le coût complet sur le cycle de vie est estimé : acquisition, exploitation, maintenance, support, formation, sécurité, **sortie**.
- [ ] Les coûts récurrents (licences, abonnements) sont inscrits au registre des contrats.

### D. Concevoir pour l'utilisateur

- [ ] Les utilisateurs concernés (usagers et/ou collaborateurs) sont impliqués avant le choix final.
- [ ] Un test d'utilisabilité, même simple, est prévu avant la mise en service.
- [ ] Les exigences d'accessibilité (eCH-0059 / WCAG) figurent dans le cahier des charges ou le contrat.
- [ ] Les publics éloignés du numérique sont pris en compte (langage clair, accompagnement, alternative).

### E. Sécuriser par défaut

- [ ] Les données traitées sont inventoriées ; les données personnelles ou sensibles sont identifiées.
- [ ] Le lieu d'hébergement et le cadre légal applicable sont connus et acceptables.
- [ ] Une analyse de risques proportionnée est réalisée (simple pour un petit outil, approfondie pour un système critique).
- [ ] La protection des données est intégrée dès la conception (minimisation, accès, journalisation).
- [ ] Les responsabilités sont clarifiées entre l'administration et le prestataire (qui fait quoi en cas d'incident ?).
- [ ] La gestion des accès et des comptes est définie (arrivées, départs, comptes à privilèges).

### F. Prestataire et contrat

- [ ] Le contrat inclut des clauses de **portabilité des données** et de **réversibilité** (format d'export, délais, coûts de sortie).
- [ ] La documentation des configurations, interfaces, API et dépendances est exigée comme livrable.
- [ ] Un transfert de connaissances vers l'administration est prévu.
- [ ] Les coûts récurrents et les coûts de sortie sont rendus visibles dans l'offre.
- [ ] Les développements spécifiques sont limités, documentés et si possible réutilisables par d'autres collectivités.
- [ ] Le niveau de dépendance au fournisseur est évalué et jugé acceptable.

### G. Partager pour économiser

*Avant de garder pour soi, partager ce qui peut servir aux autres.*

- [ ] Le cahier des charges, les clauses ou la grille d'évaluation peuvent-ils être partagés avec d'autres administrations ?
- [ ] Si un développement a lieu : la publication du code (open source) est-elle envisagée ?
- [ ] Un retour d'expérience (modèle disponible dans [exemples/](../exemples/usecase_MODELE.md)) est prévu en fin de projet.
- [ ] Les données publiques non sensibles produites pourront-elles être ouvertes (open data by default) ?

---

## Fiche de décision (à conserver)

| Rubrique | Contenu |
|---|---|
| Projet / besoin | |
| Date et responsable | |
| Options examinées | |
| Décision (réutiliser / adapter / acheter / développer) | |
| Justification | |
| Points de vigilance (sécurité, dépendance, coûts de sortie) | |
| Indicateurs suivis | |
| Partage prévu (RETEX, cahier des charges, code) | |

---

*ReUse-CH – Cadre volontaire pour une transformation numérique Responsable, Innovante et Mutualisée – Licence CC BY-SA 4.0*
