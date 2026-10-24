<div align="center">
<h1>COVID-19 & Bonheur</h1>
<p><em>Analyse de données — Impact du COVID-19 sur le bonheur mondial</em></p>
<a href="#"><img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white&style=flat-square"></a>
<a href="#"><img src="https://img.shields.io/badge/Data-Analysis-orange?style=flat-square"></a>
<a href="#"><img src="https://img.shields.io/badge/COVID--19-World%20Happiness-blueviolet?style=flat-square"></a>
<a href="#"><img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"></a>
<a href="https://ndhviet.github.io/covid/">
  <img src="https://img.shields.io/badge/Demo-Live_Website-red?style=flat-square">
</a>
<a href="#"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square"></a>
</div>
<br>

# Projet-Covid-19-Data-Analyst

## 📌 Présentation du projet

Ce projet analyse le nombre cumulé de cas confirmés de COVID-19 par pays et le combine avec des indicateurs de qualité de vie, afin d'étudier l'existence d'un lien entre la propagation du virus et le niveau de bonheur des populations.

| Source | Données utilisées | Lien |
|--------|-------------------|------|
| Johns Hopkins University | Cas confirmés cumulés de COVID-19 par pays | [Kaggle](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university) |
| World Happiness Report 2021 (Gallup / ONU) | Score de bonheur et indicateurs associés | [Kaggle](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021) |

**Outils :** Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn), Quarto, Streamlit.

---
 
## 🔍 Indicateurs analysés
 
- **GDP per capita** — Richesse économique par habitant
- **Social support** — Réseau de soutien social perçu
- **Life expectancy** — Espérance de vie en bonne santé
- **Freedom** — Liberté de faire des choix de vie
- **Generosity** — Générosité
- **Corruption perception** — Perception de la corruption

## 🗂️ Organisation du projet

1. **Partie 1 — Préparation et nettoyage :** importation, valeurs manquantes, agrégation par pays et fusion des sources
2. **Partie 2 — Analyse exploratoire (EDA) :** statistiques descriptives et visualisations de l'évolution de la pandémie
3. **Partie 3 — Corrélations et régressions :** lien entre le taux maximal d'infection et les indicateurs du World Happiness Report
4. **Partie 4 — Conclusion :** résultats, limites et pistes d'amélioration

---

## 📈 Résultats clés

- Le PIB par habitant est fortement corrélé au bonheur.
- Le soutien social améliore significativement le bien-être.
- Les cas de COVID-19 sont plus élevés dans les pays développés.
- Les modèles de régression ont une performance limitée pour expliquer le bonheur.

---

## 🚀 Lancer le projet

```sh
git clone https://github.com/ndhviet/Projet-Covid-19-Data-Analyst.git
cd Projet-Covid-19-Data-Analyst
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

```sh
quarto render          # générer le site web
streamlit run app.py   # lancer le dashboard Streamlit
```

---

## 📊 Dashboard

[![Dashboard du projet](images/dashboard_covid.png)](https://ndhviet.github.io/Projet-Covid-19-Data-Analyst/images/dashboard_covid_happiness.html)

➡️ Cliquez sur l'image pour ouvrir le dashboard interactif.



## Partie 1 : Préparation et nettoyage des données

Cette partie est consacrée à l'importation des jeux de données, au traitement des valeurs manquantes, à l'agrégation des données par pays ainsi qu'à la fusion des différentes sources de données.

## Partie 2 : Analyse exploratoire des données (EDA)

Cette étape vise à explorer les caractéristiques principales des données à l'aide de statistiques descriptives et de visualisations afin de mieux comprendre l'évolution de la pandémie dans différents pays.

## Partie 3 : Analyse de la relation COVID-19 – Bonheur

Dans cette partie, on étudie les corrélations entre le taux maximal d'infection et plusieurs indicateurs issus du World Happiness Report, tels que :

- le PIB par habitant ;
- le soutien social ;
- l'espérance de vie en bonne santé ;
- la liberté de faire des choix de vie.

## Partie 4 : Conclusion

On résume les principaux résultats obtenus, discute de leurs limites et propose des pistes d'amélioration pour des analyses futures.

## 🚀 Démo
 
👉 [Voir le site en ligne](https://ndhviet.github.io/covid/)
 
---

**Consulter le dashboard**

[![Dashboard du projet](images/dashboard_covid.png)](https://ndhviet.github.io/Projet-Covid-19-Data-Analyst/images/dashboard_covid_happiness.html)

➡️ Cliquez sur l'image pour ouvrir le dashboard interactif.

## 📌 Présentation du projet

Ce projet analyse le nombre cumulé de cas confirmés de COVID-19 par pays et le combine avec des indicateurs de qualité de vie, afin d'étudier l'existence d'un lien entre la propagation du virus et le niveau de bonheur des populations.

| Source | Données utilisées | Lien |
|--------|-------------------|------|
| Johns Hopkins University | Cas confirmés cumulés de COVID-19 par pays | [Kaggle](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university) |
| World Happiness Report 2021 (Gallup / ONU) | Score de bonheur et indicateurs associés | [Kaggle](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021) |

**Outils :** Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn), Quarto, Streamlit.

---

## 🔍 Indicateurs analysés

- **GDP per capita** — Richesse économique par habitant
- **Social support** — Réseau de soutien social perçu
- **Life expectancy** — Espérance de vie en bonne santé
- **Freedom** — Liberté de faire des choix de vie
- **Generosity** — Générosité
- **Corruption perception** — Perception de la corruption

---


