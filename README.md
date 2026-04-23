# 🏅 Analyse Tarifiaire — J.O Paris 2024

> Rapport Power BI en 3 pages analysant la politique de prix de la billetterie des Jeux Olympiques et Paralympiques de Paris 2024.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Paris 2024](https://img.shields.io/badge/Paris-2024-purple)
![Status](https://img.shields.io/badge/status-terminé-brightgreen)

---

## À propos du projet

Ce rapport Power BI explore la **politique tarifaire de la billetterie des Jeux Olympiques et Paralympiques de Paris 2024**. Il analyse comment les prix ont été segmentés selon les catégories de places, les disciplines sportives, les types d'épreuves et les créneaux horaires de compétition.

L'objectif est de mettre en lumière la logique de valorisation mise en place par Paris 2024 — depuis les cérémonies d'ouverture jusqu'aux finales paralympiques.

---

## Structure du rapport

Le rapport est composé de 3 pages :

### Page 1 — Cérémonies
- Prix moyens par **catégorie A, B, C et D** (Jeux Olympiques et Paralympiques séparés)
- Capacité maximale par site (Quais de Seine, Stade de France, Concorde)
- Carte interactive des sites de cérémonie
- Sélecteur cérémonie d'ouverture / clôture

### Page 2 — Jeux Olympiques
- Évolution temporelle intraday des prix par catégorie (graphique en aires)
- Tarification par discipline sportive (barres horizontales groupées)
- Tarification par épreuve (Athlétisme détaillé, etc.)
- Filtre dynamique par jour de compétition

### Page 3 — Jeux Paralympiques
- Tarification par discipline paralympique
- Tarification par épreuve
- Répartition médailles vs qualifications (graphique donut)
- Comparaison des prix moyens par catégorie

---

## Captures d'écran

| Cérémonies | Jeux Olympiques | Jeux Paralympiques |
|---|---|---|
| *(screenshot_01.png)* | *(screenshot_02.png)* | *(screenshot_03.png)* |

---

## Insights principaux

- **Écart cérémonies JO/Para** : La Cat A atteint 2 700 € pour les JO contre 550 € pour les Jeux Paralympiques (×5)
- **Discipline la plus chère (JO)** : Natation en Cat A avec 572 €, devant l'Athlétisme (501 €) et la Gymnastique artistique (454 €)
- **Pics tarifaires** : Les prix culminent en soirée (autour de 21h) et lors des sessions de finales (Cat A > 700 €)
- **Para Cyclisme** : Discipline paralympique la plus valorisée avec 70 € en Cat A
- **Cat D accessible** : La billetterie grand public démarre à 45 € pour les cérémonies paralympiques et à 500 € pour les cérémonies olympiques

---

## Stack technique

| Outil | Usage |
|---|---|
| Power BI Desktop | Création du rapport et des visualisations |
| DAX | Mesures calculées (prix moyens, agrégations) |
| Power Query (M) | Nettoyage et transformation des données |
| Bing Maps | Carte des sites de compétition |
| Source Paris 2024 | Données de billetterie officielle |

---

## Utilisation

```bash
git clone https://github.com/votre-username/jo-paris-2024-tarifs.git
```

Ouvrir le fichier `.pbix` avec **Power BI Desktop** (version mai 2024 ou supérieure recommandée).

---

## Auteur

Réalisé dans le cadre d'une analyse personnelle des Jeux Olympiques de Paris 2024.  
N'hésitez pas à ⭐ le repo si le projet vous a été utile !
