# Analysis-Bike-Buyers
# 🚲 Analyse des acheteurs de vélos (Bike Buyers)

Analyse Excel d'un jeu de données clients pour comprendre qui achète un vélo et pourquoi, à partir de leurs caractéristiques démographiques et socio-professionnelles.

## Contexte

Un magasin de vélos dispose des données de 1026 clients (âge, revenu, statut marital, profession, région, distance de trajet domicile-travail...) et souhaite savoir quel profil de client achète le plus.

## Ce que contient le fichier

| Feuille | Contenu |
|---|---|
| bike_buyers | Données brutes, telles que reçues (1026 lignes) |
| Worksheet | Données nettoyées : codes décodés (M → Married, F → Female...), doublons retirés (1000 lignes), et une colonne Age Brackets créée pour regrouper les clients en Youth / Adult / Old |
| pivot table | Tableau croisé dynamique (revenu moyen par genre et par achat) |
| Dashboard | Dashboard interactif avec graphiques et segments (slicers) |

## Méthode

- Nettoyage des données brutes (décodage des abréviations, suppression des doublons)
- Création d'une variable de tranche d'âge par classification (Youth, Adult, Old)
- Tableau croisé dynamique pour croiser revenu, genre et décision d'achat
- Dashboard avec segments interactifs pour explorer les résultats par région, profession, genre...

## Principaux résultats

- 47 % des clients ont acheté un vélo (481 sur 1000)
- Les clients Adult achètent nettement plus (54 %) que les Youth (36 %) et les Old (34 %)
- La région Pacific a le taux d'achat le plus élevé (59 %), contre 43 % en Amérique du Nord
- Les professions Professional achètent le plus (54 %), devant Clerical (50 %)
- Le revenu moyen est légèrement plus élevé chez les hommes (58 063) que chez les femmes (54 581)

## Outils utilisés

Excel : nettoyage de données, tableaux croisés dynamiques, segments (slicers), mise en forme conditionnelle, dashboard interactif.

<img width="1237" height="680" alt="image" src="https://github.com/user-attachments/assets/d607cbdd-afda-49c7-baa1-0a2f63774e98" />
<img width="1067" height="578" alt="image" src="https://github.com/user-attachments/assets/cab91de0-e0d6-40be-9227-b748ea6f10e7" />
<img width="1061" height="632" alt="image" src="https://github.com/user-attachments/assets/797df08b-fefb-4379-9308-6cc274bec76b" />


