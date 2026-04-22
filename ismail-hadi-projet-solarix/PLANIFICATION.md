## Analyse de la maquette

- Le menu à gauche
- L'en-tête avec le titre, le sous-titre et les boutons.
- La carte de la progression de l'aube.
- Les cartes des quêtes.

## Nomenclature CSS prévue

#### Header

.header <br>
.header__title  <br>
.header__subtitle  <br>
.header__button  <br>

#### Menu

.menu <br>
.menu__icon <br>
.menu__title <br>
.menu__subtitle <br>
.menu__button <br>
.menu__button--hover <br>
.menu__button__icon <br>

#### Progress Card

.progress-card <br>
.progress-card__icon <br>
.progress-card__subtitle <br>
.progress-card__title <br>
.progress-card__percentage <br>
.progress-card__progress-line <br>
.progress-card__quote <br>

#### Quest Card

.quest-card <br>
.quest-card__button <br>
.quest-card__status--hover <br>
.quest-card__title <br>
.quest-card__text <br>
.quest-card__xp__progress <br>
.title__quest-card <br>
.subtitle__quest-card <br>

## Découpage
Je vais d'abord coder les différentes sections de la page en respectant ma structure de nommage, tout en notant mes blocages au fur et à mesure. Je passerai ensuite au CSS avec une stratégie de (mobile-first). Une fois la base établie, je m’attaquerai aux ajustements pour rendre le site entièrement responsive.

## Responsive
La structure évoluera de la manière suivante : le menu passera de la gauche au bas de l’écran. L’en-tête sera simplifié pour ne garder qu'une icône, un titre et un bouton. Enfin, les cartes de progression et les cartes de quêtes passeront d'un affichage horizontal à un affichage vertical. 

## Zone libre
Pour la zone libre, je vais mettre quatre petites cartes réparties sur deux lignes. Chaque carte affichera simplement le nom de la catégorie en titre, suivi de la réponse en texte.
