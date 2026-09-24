# Repères Québec 2026

Plateforme comparative pour l'élection générale québécoise de 2026 (5 octobre 2026), couvrant les cinq principaux partis : CAQ, PCQ, PLQ, PQ et QS.

## Statut

**Positions de partis documentées et sourcées. Candidats : profils complets pour les 5 chefs et leurs 20 adversaires directs (5 circonscriptions) ; gabarit vide pour le reste.** Les six dimensions, les couches analytiques et l'indice « Québec d'abord » sont codés pour les 5 partis à partir de la couverture de la campagne, avec une source citée sous chaque position. Voir « Sources et méthode » ci-dessous.

## Contenu

[`index.html`](index.html) — application à page unique (une seule page HTML, navigation par « pages » internes en JS, pas de défilement continu) avec cinq vues :

- **Accueil** — page de repère qui dirige vers les quatre sections suivantes.
- **Partis** — analyse par parti, filtrable (CAQ/PCQ/PLQ/PQ/QS) : positionnement sourcé sur les six dimensions, couches analytiques (saillance, rhétorique populiste, transparence budgétaire, compatibilité de coalition) et indice « Québec d'abord ».
- **Enjeux** — comparatif par enjeu, filtrable par dimension : pour l'enjeu choisi, les cinq partis triés et positionnés côte à côte. Volontairement descriptif, pas de verdict — la plateforme montre les positions, le lecteur juge qui sert le mieux ses priorités pour le Québec.
- **Candidats** — profils par parti : complets et sourcés pour les 5 chefs (Fréchette/Trois-Rivières, Duhaime/Bellechasse, Milliard/Orford, St-Pierre Plamondon/Camille-Laurin, Ghazal/Mercier) et leurs 20 adversaires directs (nom + circonscription confirmés, biographie à documenter) ; gabarit vide pour les ~100 autres circonscriptions.
- **Méthodologie** — grille de notation complète, méthodologie des couches analytiques, liste des champs de métadonnées additionnels, construction de l'indice « Québec d'abord », et note d'architecture i18n (`fr-CA` comme seule locale active pour l'instant).

## Sources et méthode

Les positions de partis ont été codées le **23 septembre 2026** à partir de la couverture journalistique de la campagne (Le Devoir, La Presse, Radio-Canada, Noovo Info, Les Affaires, Le Quotidien, entre autres) — chaque position cite sa source directement dans l'interface. La campagne se poursuit jusqu'au vote du 5 octobre 2026 : c'est un instantané, pas un résultat final, et certaines cellules sont marquées comme peu documentées faute de couverture suffisante au moment de la recherche. Ce squelette n'a pas vocation à être mis à jour en continu ; à revérifier avant toute utilisation après le 5 octobre.

## Consulter le site

Ouvrir [`index.html`](index.html) dans un navigateur, ou consulter la version publiée : https://claude.ai/artifact/28VBR4tNuypKX52TovQAkE

## À venir

- Profils de candidats pour Montréal (~27 circonscriptions), Laval (6), Montérégie/Rive-Sud (~17), Laurentides-Lanaudière/Rive-Nord (~14) et la région de Québec (~11) — environ 70 à 90 circonscriptions supplémentaires (~350-450 candidat·e·s), à traiter par lots dans des passes de recherche ultérieures.
- Biographies complètes (âge, profession, études) pour les 20 adversaires des chefs déjà identifié·e·s.
- Vérification indépendante des cellules marquées « peu documenté ».
- Mise à jour des positions si des changements significatifs surviennent avant le 5 octobre 2026.
