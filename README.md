[![Contributeurs][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Problèmes][issues-shield]][issues-url]
[![Licence MIT][license-shield]][license-url]

<!-- LOGO DU PROJET -->
<br />
<p align="center">
  <a href="https://github.com/tukadi/reZonance">
    <img src="STATIC_IMG/head.svg" alt="Logo" width="420" height="420">
  </a>



<!-- TABLE DES MATIÈRES -->
## Table des matières

* [À propos du projet](#about-the-project)
  * [Filtrage basé sur le contenu](#Filtrage basé sur le contenu)
  * [Similarité de cosinus](#Similarité de cosinus)
  * [Avantages](#Avantage-sur-filtrage-collaboratif)
* [Mise en route](#getting-started)
  * [Prérequis](#prérequis)
  * [Installation](#installation)
* [Utilisation](#utilisation)
* [Feuille de route](#feuille de route)
* [Contribuer](#contribuer)
* [Contact](#contact)



<!-- À PROPOS DU PROJET -->
## À propos du projet

[![Product Name Screen Shot][product-screenshot]](https://example.com)

<strong>reZonance</strong> est un <strong>service de recommandation basé sur le contenu</strong> qui suggère des chansons similaires à celle choisie par l'utilisateur. Il contient environ *160 000 chansons* dans sa base de données et prend environ *300ms pour générer des recommandations*.

## Voici quelques concepts de base sur lesquels ce projet s'appuie

</br>

* ### Filtrage basé sur le contenu

Le filtrage basé sur le contenu utilise des fonctionnalités d'éléments pour recommander d'autres éléments similaires à ce que l'utilisateur aime, en fonction de ses actions précédentes ou de ses commentaires explicites.

<img src = "STATIC_IMG/content.jpg" height="360" width="480">

<br />

* ### Similitude de cosinus

La similarité en cosinus mesure la similarité entre deux vecteurs en calculant le cosinus de l'angle entre eux. Une visualisation simple et la formule peuvent être trouvées ci-dessous.

<img src = "STATIC_IMG/cosinus.png" height="360" width="480">

<br />


### Avantage par rapport au filtrage collaboratif
<p>
  Les moteurs de recommandation qui fonctionnent sur le filtrage collaboratif recommandent chaque article (produits annoncés sur votre site) en fonction des actions des utilisateurs. Plus un élément a d'actions utilisateur, plus il est facile de dire quel utilisateur serait intéressé par cet élément et quels autres éléments lui sont similaires. Au fil du temps, le système sera en mesure de donner des recommandations de plus en plus précises.
</p>
<p>
  Ceci, cependant, apporte une contradiction et une difficulté majeures aux sites classés et à leurs moteurs de recommandation. Même si une nouvelle chanson peut en fait être la plus pertinente pour un utilisateur, un système de recommandation a beaucoup moins confiance en les recommander qu'avec les anciennes chansons, mais ce n'est tout simplement pas une bonne idée de laisser les annonces de chansons dominer le processus de recommandation. .
</p>

<p>

  De même, les utilisateurs plus récents ne peuvent pas recevoir de recommandations précises tant que l'utilisateur n'a pas fait lui-même quelques choix qui ajusteront l'algorithme de recommandation.

## Construit avec

</br>

<p float = "gauche">

<img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />

<img alt="pandas" src="https://img.shields.io/badge/-pandas-150458?style=flat-square&logo=pandas&logoColor=white">


<img alt="JS" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">


<img alt="React" src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=white" />

<img alt="Heroku" src="https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=white" />



</p>


<!-- POUR COMMENCER -->
## Commencer

Pour obtenir une copie locale opérationnelle, suivez ces exemples d'étapes simples.

### Conditions préalables

* Réagir
* Python 3.6+


### Installation

<br />

#### API de flacon
<br />

1. Cloner le dépôt
```sh
git clone https://github.com/tukadi/reZonance
```

2. Configuration requise pour l'installation
```sh
pip3 install -r requirements.txt
```

3. Démarrez le serveur Flask (par défaut à `localhost:5000`)
```sh
python3 app.py
```

<br />

#### Réagir

<br />

1. Cloner le dépôt
```sh
git clone https://github.com/tukadi/reZonance
```

2. Installez les packages requis
```sh
client cd
npm installer
```

3. Démarrez le serveur de développement React (par défaut à `localhost:3000`)
```sh
démarrage npm
```

<br />



<!-- EXEMPLES D'UTILISATION -->
## Utilisation


* ### Visitez le [site web](https://rezonance.vercel.app) et cliquez sur démarrer

<img src="STATIC_IMG/ss1.png">

* ### Entrez le nom de la chanson ou le nom de l'artiste pour lequel vous souhaitez rechercher des chansons similaires. Cliquez sur une carte pour choisir une chanson.

<img src="STATIC_IMG/ss2.png">


* ### Dans la page de recommandation, cliquez sur