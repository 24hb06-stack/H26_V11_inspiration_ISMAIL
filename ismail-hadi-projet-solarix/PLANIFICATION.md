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

.menu
.menu__icon
.menu__title
.menu__subtitle
.menu__button
.menu__button--hover
.menu__button__icon

#### Progress Card

.progress-card
.progress-card__icon
.progress-card__subtitle
.progress-card__title
.progress-card__percentage
.progress-card__progress-line
.progress-card__quote

#### Quest Card

.quest-card
.quest-card__button
.quest-card__status--hover
.quest-card__title
.quest-card__text
.quest-card__xp__progress
.title__quest-card
.subtitle__quest-card

## Découpage
D'abord, je vais coder les différentes parties de la page web en respectant ma nomenclatue. En même temps, je vais noter mes difficultés sur le journal. Ensuite, je vais coder le CSS sans pensée au responsive. Le CSS sera mobile-first. Finalement, je vais rendre le code responsive.

## Responsive
Le menu va passer de la gauche à en bas de la page. L'en-tête va passer de un titre, un sous-titre et deux bouttons à un icon, un titre, et un bouton. La carte de la progrssion va passer de horizontale à la verticale. Finalement, les carte des quêtes vont passer de l'horizontale à la verticale.

## Zone libre
Pour la zone libre, je vais faire quatres cartes plus petites qui vont être reparties sur deux lignes. Il y aura simplement un titre avec le nom de la catégorie et un texte qui dit la réponse.
