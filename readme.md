#  **Analyse Stratégique du Marché Immobilier en Tunisie**

Bienvenue dans ce projet d'analyse exploratoire des données (EDA) dédié au secteur immobilier tunisien. Ce travail a pour but de décrypter les dynamiques de prix, d'identifier les zones à forte valeur ajoutée et de comprendre comment la géographie influence le marché foncier actuel.

##  **À propos du projet**

Le marché immobilier en Tunisie est complexe et marqué par des contrastes importants entre les régions. Plutôt que de se limiter à une simple lecture des prix de vente, ce projet propose une immersion statistique pour transformer des données brutes en indicateurs décisionnels.

L'accent a été mis sur la création d'une métrique clé : **le prix au mètre carré (**$m^2$**)**, seul véritable indicateur de la pression foncière, permettant de comparer objectivement des biens de surfaces différentes à travers le pays.

##  **Ce que nous cherchons à comprendre**

À travers ce dépôt, j'explore quatre axes majeurs :

1. **La structure des prix :** Comment se répartit l'offre entre l'immobilier résidentiel standard et le segment de luxe ?  
2. **L'impact de la surface :** Jusqu'à quel point la taille d'un bien dicte-t-elle son prix final ?  
3. **Les disparités régionales :** Quelles sont les zones "Premium" où la demande tire les prix vers le haut ?  
4. **La vitalité du marché :** Quels gouvernorats affichent le volume d'annonces le plus élevé ?

##  **Structure des données**

Le dataset regroupe plusieurs variables essentielles pour l'analyse :

* price : Prix du bien (en TND).  
* area : Surface habitable ($m^2$).  
* governorate : Localisation (Tunis, Ariana, Sousse, etc.).  
* room : Configuration du logement (nombre de pièces).  
* price\_m2 : Indicateur de valeur foncière réelle (calculé).

##  **Coulisses techniques**

Ce projet a été entièrement développé avec l'écosystème **R**, en privilégiant la lisibilité et l'interactivité :

* **Manipulation :** tidyverse (dplyr) pour un nettoyage rigoureux des données.  
* **Visualisation :** ggplot2 pour les graphiques statiques et plotly pour l'exploration interactive.  
* **Reporting :** Généré via Quarto pour un rendu professionnel et reproductible.

##  **Enseignements majeurs**

L'analyse révèle que si la majorité des transactions se concentrent sous la barre des **500 000 TND**, les écarts de prix au $m^2$ entre le Grand Tunis et les zones périphériques confirment une forte centralisation de la valeur foncière dans les pôles économiques et côtiers.

**Réalisé par :** Chaima Hajri

*Projet académique d'analyse de données.*