# Repères Québec 2026

Plateforme comparative pour l'élection générale québécoise de 2026 (5 octobre 2026), couvrant les cinq principaux partis : CAQ, PCQ, PLQ, PQ et QS.

## Statut

**Positions de partis documentées et sourcées. Candidats : 235 personnes confirmées dans 47 circonscriptions (5 chefs + adversaires + Mauricie, Laval, Chaudière-Appalaches, Estrie, Capitale-Nationale, Centre-du-Québec et Outaouais complètes) ; gabarit vide pour le reste.** Expansion en cours, région par région, dans l'ordre : Mauricie ✅ → Laval ✅ → Chaudière-Appalaches ✅ → Estrie ✅ → Capitale-Nationale ✅ → Centre-du-Québec ✅ → Outaouais ✅ → Saguenay-Lac-Saint-Jean → Bas-Saint-Laurent → Abitibi-Témiscamingue → Côte-Nord/Gaspésie/Nord-du-Québec → Laurentides → Lanaudière → Montérégie → Montréal. Les six dimensions, les couches analytiques et l'indice « Québec d'abord » sont codés pour les 5 partis à partir de la couverture de la campagne, avec une source citée sous chaque position. Voir « Sources et méthode » ci-dessous.

## Contenu

[`index.html`](index.html) — application à page unique (une seule page HTML, navigation par « pages » internes en JS, pas de défilement continu) avec cinq vues :

- **Accueil** — page de repère qui dirige vers les quatre sections suivantes.
- **Partis** — analyse par parti, filtrable (CAQ/PCQ/PLQ/PQ/QS) : positionnement sourcé sur les six dimensions, couches analytiques (saillance, rhétorique populiste, transparence budgétaire, compatibilité de coalition) et indice « Québec d'abord ».
- **Enjeux** — comparatif par enjeu, filtrable par dimension : pour l'enjeu choisi, les cinq partis triés et positionnés côte à côte. Volontairement descriptif, pas de verdict — la plateforme montre les positions, le lecteur juge qui sert le mieux ses priorités pour le Québec.
- **Candidats** — gabarit complet (12 champs), en deux modes de consultation : *par parti* (filtre CAQ/PCQ/PLQ/PQ/QS) ou *par circonscription* (47 circonscriptions couvertes pour l'instant, dont les régions complètes de la Mauricie, de Laval, de Chaudière-Appalaches, de l'Estrie, de la Capitale-Nationale, du Centre-du-Québec et de l'Outaouais). Profils complets et sourcés pour les 6 chefs/coporte-parole de parti (incluant Sol Zanetti, coporte-parole de QS, candidat dans Jean-Lesage) ; nom + circonscription confirmés pour les 229 autres candidat·e·s (biographie documentée quand l'information publique le permettait) ; gabarit vide pour les 80 autres circonscriptions.
- **Méthodologie** — grille de notation complète, méthodologie des couches analytiques, liste des champs de métadonnées additionnels, construction de l'indice « Québec d'abord », et note d'architecture i18n (`fr-CA` comme seule locale active pour l'instant).

## Sources et méthode

Les positions de partis ont été codées le **23 septembre 2026** à partir de la couverture journalistique de la campagne (Le Devoir, La Presse, Radio-Canada, Noovo Info, Les Affaires, Le Quotidien, entre autres) — chaque position cite sa source directement dans l'interface. La campagne se poursuit jusqu'au vote du 5 octobre 2026 : c'est un instantané, pas un résultat final, et certaines cellules sont marquées comme peu documentées faute de couverture suffisante au moment de la recherche. Ce squelette n'a pas vocation à être mis à jour en continu ; à revérifier avant toute utilisation après le 5 octobre.

## Consulter le site

Ouvrir [`index.html`](index.html) dans un navigateur, ou consulter la version publiée : https://claude.ai/artifact/28VBR4tNuypKX52TovQAkE

## À venir

- Profils de candidats pour les 80 circonscriptions restantes, région par région (voir l'ordre dans « Statut » ci-dessus) — au total, les 5 partis dans les 127 circonscriptions du Québec (confirmé via Wikipédia « Liste des circonscriptions provinciales du Québec par région » et Le Québec Vote).
- Biographies plus complètes (âge, études) pour les candidat·e·s dont seul le nom/circonscription/parti est confirmé pour l'instant.
- Vérification indépendante des cellules marquées « peu documenté ».
- Mise à jour des positions si des changements significatifs surviennent avant le 5 octobre 2026.
