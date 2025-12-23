🎵 Featurings et visibilité algorithmique sur YouTube
📌 Description

Ce projet analyse le rôle des featurings dans le rap français comme levier de visibilité algorithmique sur YouTube.
À partir d’un web scraping systématique des recommandations YouTube, il vise à mesurer empiriquement si les collaborations entre artistes créent des ponts algorithmiques entre leurs audiences.

🎯 Problématique

Le featuring est historiquement une pratique centrale du rap, reposant sur des logiques de reconnaissance artistique, d’authentification professionnelle et de capital symbolique.
Avec l’essor des plateformes de streaming et des algorithmes de recommandation, se pose une question centrale :

Les featurings sont-ils devenus des outils d’optimisation algorithmique de la visibilité ?

Ce projet interroge la manière dont les logiques sociales et artistiques du featuring sont reconfigurées par les algorithmes.

🧠 Cadre théorique

L’analyse s’appuie notamment sur les travaux de Corentin Roquebert sur le rap français, qui conceptualise le featuring comme un double échange symbolique :

authentification professionnelle

reconnaissance artistique

L’objectif est d’examiner comment ces mécanismes traditionnels se transforment dans un environnement dominé par les systèmes de recommandation automatisée.

🗂️ Données et méthodologie
📊 Échantillon

60 collaborations de rap français

30 featurings entre artistes établis (+5M de vues en moyenne)

30 featurings impliquant au moins un artiste émergent (-500k vues)

Pour chaque collaboration :

1 clip solo récent de chaque artiste
➡️ 180 vidéos analysées

🕸️ Web scraping

Plateforme : YouTube

Données collectées :

20 recommandations par vidéo

Navigation :

mode anonyme + VPN

Total :

3 600 recommandations collectées

Le scraping vise à limiter les biais liés à l’historique utilisateur et à observer le fonctionnement « brut » de l’algorithme.

📐 Variable étudiée

Recommandation croisée :

1 = l’artiste collaborateur apparaît dans les recommandations

0 = absence de l’artiste collaborateur

📈 Analyse statistique

L’analyse repose sur :

comparaison des proportions

test du chi-deux (χ²) pour mesurer la significativité

V de Cramer pour estimer la taille d’effet

📊 Résultats principaux
🎤 Artistes établis

Recommandations croisées (solo) : 9,3 %

Recommandations croisées (collaboration) : 35,0 %

+25,7 points

χ² = 179,40 | p < 0,001

Effet fort (V = 0,316)

🌱 Artistes émergents

Recommandations croisées (solo) : 8,3 %

Recommandations croisées (collaboration) : 20,2 %

+11,9 points

χ² = 52,95 | p < 0,001

Effet moyen (V = 0,172)

🔍 Interprétation

Les résultats confirment que :

les featurings créent des connexions algorithmiques mesurables

l’effet est plus fort pour les artistes établis

les collaborations multiplient la visibilité croisée :

×4 chez les établis

×2,4 chez les émergents

Ces résultats valident empiriquement l’existence de ponts algorithmiques entre artistes collaborateurs.

⚠️ Limites

Algorithmes YouTube opaques et évolutifs

Catégories « établi / émergent » simplificatrices

Analyse non longitudinale

Échantillon limité au rap français

🧩 Enjeux sociologiques

L’efficacité algorithmique du featuring soulève une tension :

logique artistique et sociale

logique d’optimisation de la visibilité

Certains acteurs du milieu dénoncent une instrumentalisation marketing, tandis que d’autres intègrent pleinement ces logiques dans leurs stratégies professionnelles.

🧠 Conclusion

Le featuring demeure une pratique sociale centrale du rap, mais l’environnement algorithmique ajoute une nouvelle dimension :

l’optimisation mesurable de la visibilité

Cette évolution ne supprime pas les logiques traditionnelles, mais les reconfigure.
L’enjeu pour les artistes réside dans leur capacité à négocier entre créativité, reconnaissance symbolique et performance algorithmique.

🛠️ Outils utilisés

Python

Web scraping

Analyse statistique (χ², V de Cramer)

Analyse sociologique du numérique
