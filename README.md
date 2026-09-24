# Repères Québec 2026

Squelette méthodologique d'une plateforme comparative pour l'élection générale québécoise de 2026, couvrant les cinq principaux partis : CAQ, PCQ, PLQ, PQ et QS.

## Statut

**Squelette uniquement — aucune donnée n'est remplie.** Ce dépôt contient la structure, les gabarits et la méthodologie, pas de profils de candidats, de scores de partis ni de sources individuelles.

## Contenu

[`index.html`](index.html) — application à page unique (une seule page HTML, navigation par « pages » internes en JS, pas de défilement continu) avec cinq vues :

- **Accueil** — page de repère qui dirige vers les quatre sections suivantes.
- **Partis** — analyse par parti, filtrable (CAQ/PCQ/PLQ/PQ/QS)&nbsp;: positionnement sur les six dimensions, couches analytiques et indice « Québec d'abord » (valeurs vides — gabarit uniquement).
- **Enjeux** — comparatif par enjeu, filtrable par dimension&nbsp;: pour l'enjeu choisi, positionnement des cinq partis côte à côte. Volontairement descriptif, pas de verdict&nbsp;— la plateforme montre les positions, le lecteur juge qui sert le mieux ses priorités.
- **Candidats** — gabarit de profils de candidats, filtrable par parti (table vide, aucune ligne remplie).
- **Méthodologie** — grille de notation complète, méthodologie des couches analytiques (saillance, rhétorique populiste selon Cas Mudde, transparence budgétaire, compatibilité de coalition), liste des champs de métadonnées additionnels, construction de l'indice « Québec d'abord », et note d'architecture i18n (`fr-CA` comme seule locale active pour l'instant).

## Consulter le site

Ouvrir [`index.html`](index.html) dans un navigateur, ou consulter la version publiée : https://claude.ai/artifact/28VBR4tNuypKX52TovQAkE

## À venir

- Collecte et remplissage des données de candidats (sites des partis, dépôts d'Élections Québec, réseaux sociaux).
- Codage des scores de partis sur la grille et les couches analytiques.
- Liens de sourçage individuels par candidat·e.
