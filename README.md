# 🎵 Featurings et visibilité algorithmique sur YouTube

## 📌 Présentation du projet
Ce projet analyse l’impact des **featurings dans le rap français** sur la **visibilité algorithmique sur YouTube**.  
Il s’inscrit à la croisée de la **data analysis**, du **web scraping** et de la **sociologie des plateformes**, en interrogeant la manière dont les collaborations artistiques influencent les recommandations automatisées.

---

## ❓ Problématique
**Les featurings créent-ils des « ponts algorithmiques » mesurables entre les audiences des artistes sur YouTube ?**

L’objectif est d’évaluer empiriquement si une collaboration augmente la probabilité qu’un artiste apparaisse dans les recommandations de l’autre.

---

## 🕸️ Collecte des données (Web Scraping)
Les données ont été collectées directement sur **YouTube**, en navigation anonyme afin de limiter les biais liés à l’historique de navigation.

- Plateforme : YouTube  
- Méthode : navigation anonyme (VPN)  
- Recommandations collectées : 20 par vidéo  
- Total : 3 600 recommandations analysées  

### 📦 Échantillon
- 60 featurings de rap français  
  - 30 collaborations entre artistes **établis**  
  - 30 collaborations impliquant au moins un artiste **émergent**
- Pour chaque collaboration :
  - 1 clip collaboratif
  - 1 clip solo récent par artiste

➡️ **180 vidéos analysées au total**

---

## 📊 Variables étudiées
- **Recommandation croisée**
  - `1` : l’artiste collaborateur apparaît dans les recommandations
  - `0` : absence de recommandation croisée

---

## 📈 Méthodologie d’analyse
- Comparaison entre :
  - vidéos solo
  - vidéos collaboratives
- Tests statistiques :
  - test du **chi-deux (χ²)**
  - **V de Cramer** pour mesurer la taille d’effet

Cette approche permet de distinguer les effets significatifs des variations dues au hasard.

---

## 🔍 Résultats

### Artistes établis
- Solo : 9,3 % de recommandations croisées  
- Collaboration : 35,0 %  
- Différence : +25,7 points  

χ² = 179,40  
p-value < 0,001  
V de Cramer = 0,316 (effet fort)

### Artistes émergents
- Solo : 8,3 % de recommandations croisées  
- Collaboration : 20,2 %  
- Différence : +11,9 points  

χ² = 52,95  
p-value < 0,001  
V de Cramer = 0,172 (effet moyen)

---

## ✅ Conclusion
Les featurings constituent un **levier algorithmique statistiquement significatif** sur YouTube.  
Ils créent des connexions mesurables entre les univers artistiques des collaborateurs, avec un effet particulièrement marqué pour les artistes établis.

Cette dynamique illustre la manière dont les **logiques algorithmiques** reconfigurent des pratiques artistiques historiquement fondées sur des relations sociales et symboliques.

---

## ⚠️ Limites
- Opacité et évolution constante des algorithmes YouTube  
- Catégorisation « établi / émergent » simplifiée  
- Analyse non longitudinale  

---

## 🚀 Pistes d’amélioration
- Analyse sur une période plus longue  
- Comparaison avec d’autres plateformes (Spotify, TikTok)  
- Extension à d’autres genres musicaux  

---

## 🛠️ Technologies utilisées
- Python  
- Web scraping  
- Pandas / NumPy  
- Analyse statistique (χ², V de Cramer)
