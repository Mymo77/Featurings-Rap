🎵 Featurings et visibilité algorithmique sur YouTube
📌 Présentation du projet

Ce projet vise à analyser l’impact des featurings dans le rap français sur la visibilité algorithmique sur YouTube.
L’objectif est de comprendre comment les collaborations artistiques influencent les recommandations automatisées et contribuent à la circulation des audiences entre artistes.

Cette analyse s’inscrit à la croisée de la data analysis, du web scraping et de la sociologie des plateformes.

❓ Problématique

Les featurings créent-ils des « ponts algorithmiques » mesurables entre les audiences des artistes sur YouTube ?

Autrement dit :
les collaborations augmentent-elles la probabilité qu’un artiste apparaisse dans les recommandations de l’autre ?

🕸️ Collecte des données (Web Scraping)

Les données ont été collectées directement depuis YouTube, en navigation anonyme afin de limiter les biais algorithmiques.

Plateforme : YouTube

Méthode : navigation anonyme (VPN)

Recommandations analysées : 20 par vidéo

Total : 3 600 recommandations

📦 Échantillon

60 featurings de rap français

30 collaborations entre artistes établis

30 collaborations impliquant au moins un artiste émergent

Pour chaque collaboration :

1 clip collaboratif

1 clip solo récent par artiste
➡️ 180 vidéos analysées

📊 Variables étudiées

Recommandation croisée :

1 : l’artiste collaborateur apparaît dans les recommandations

0 : absence de recommandation croisée

📈 Méthodologie d’analyse

Comparaison entre :

Vidéos solo

Vidéos collaboratives

Tests statistiques :

Chi-deux (χ²)

V de Cramer (taille d’effet)

Cette approche permet d’évaluer la significativité statistique des différences observées.

🔍 Résultats principaux
Artistes établis

Recommandations croisées (solo) : 9,3 %

Recommandations croisées (feat) : 35,0 %

+25,7 points

χ² = 179,40 — p < 0,001

V de Cramer = 0,316 (effet fort)

Artistes émergents

Recommandations croisées (solo) : 8,3 %

Recommandations croisées (feat) : 20,2 %

+11,9 points

χ² = 52,95 — p < 0,001

V de Cramer = 0,172 (effet moyen)

✅ Conclusion

Les résultats confirment que les featurings augmentent significativement la visibilité algorithmique sur YouTube.
Les collaborations agissent comme de véritables leviers de diffusion algorithmique, en particulier pour les artistes déjà établis.

Ce projet met en évidence la manière dont les logiques algorithmiques reconfigurent des pratiques artistiques historiquement fondées sur des réseaux sociaux et symboliques.

⚠️ Limites

Algorithmes YouTube évolutifs et partiellement opaques

Catégorisation « établi / émergent » simplifiée

Analyse transversale (non longitudinale)

🚀 Pistes d’amélioration

Étendre l’analyse à d’autres genres musicaux

Ajouter une dimension temporelle

Comparer plusieurs plateformes (Spotify, TikTok)

🛠️ Technologies utilisées

Python

Web scraping

Analyse statistique (χ², V de Cramer)

Pandas / NumPy / Matplotlib
