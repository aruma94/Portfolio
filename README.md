🏠⚡ De la donnée brute à la décision énergétique — comment j'ai analysé la consommation de gaz d'une maison de repos

Dans le cadre d'un projet personnel, j'ai mené une analyse complète de la consommation énergétique d'un site résidentiel de type maison de repos. L'objectif : transformer des milliers de relevés horaires en insights actionnables.

🔍 Ce que j'ai fait :

📦 Extraction des données via SQL dans DBeaver, directement intégrée dans R
📈 Analyse des séries temporelles et visualisation de la consommation heure par heure
🌡️ Modélisation par régression linéaire avec les degrés-jours de chauffage
🔀 Comparaison de modèles additifs vs. modèles avec interactions (mois comme facteur)
🧩 Réduction de dimension par PCA et segmentation par clustering
📊 Synthèse dans un dashboard interactif et un rapport structuré sous R Markdown / Quarto

💡 Ce que les données révèlent :

❄️ L'hiver concentre 34% de la consommation totale — sans surprise, mais la visualisation le rend frappant
🌡️ En dessous de 0°C, la consommation horaire moyenne dépasse 1 kWh — au-dessus de 25°C, elle chute à 0,17 kWh
📉 Une tendance à la baisse est visible entre 2023 et 2025, signe potentiel d'efforts d'efficacité énergétique
🕗 Les pics de consommation se situent systématiquement entre 7h et 10h le matin, quelle que soit la saison

Ce projet m'a permis de mettre en pratique un pipeline data complet — de l'extraction jusqu'à la communication des résultats — dans un contexte concret et à fort impact social.

🛠️ Stack utilisée : R · SQL · DBeaver · ggplot2 · R Markdown · PowerBI
