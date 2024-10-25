# South Village Run Club Web Page

## Description
Ce projet propose une page Web pour un club de course local, le South Village Run Club, visant à informer les visiteurs des activités, événements et partenaires du club. La page met en avant un design réactif, optimisé pour une expérience utilisateur sur mobile, tablette et bureau.

## Technologies utilisées
**HTML5** : pour la structure sémantique de la page.

**CSS3** : pour le style et la mise en page, avec un accent sur la réactivité.

**Responsive Web Design** : pour une mise en page adaptable sur différentes tailles d'écrans (unités relatives, pourcentages, media queries).

## Fonctionnalités
**Mise en page réactive** : Utilisation des unités relatives em et rem pour la dimension et l'espacement des éléments (par exemple, width, padding).

**Adaptation des images** : Utilisation de width en pourcentages pour ajuster les images en fonction de la taille d'écran, avec des points d’arrêt définis dans les règles @media.

**Composants de navigation** : Navigation flexible et organisée pour s'adapter aux tailles d'écrans plus petites (menu passant de l'alignement horizontal à la colonne).

## Guide de conception réactive
1. **Points d'arrêt principaux**
 - **768px et 1024px** : Ces seuils permettent des ajustements spécifiques, notamment pour l'affichage des images, des titres, et de la barre de navigation.

**Photos** : Passent d'une disposition en grille à une disposition en colonne sur les écrans étroits pour faciliter la visibilité.

**Navigation** : Passe d'une orientation horizontale à verticale sur les petits écrans.

## Instructions
   1. **Cloner le dépot**
      git clone https://github.com/aemetil/South-Village-Run-Club.git
   2. **Ouvrir le fichier** index.html dans un navigateur pour visualiser la page.

## Structure du fichier
  - index.html : Fichier principal HTML contenant la structure et les sections de la page.
  - ressources/styles.css : Fichier CSS qui comprend le style et les règles de mise en page, ainsi que les requêtes multimédias.
  - ressources/images : Fichier contenant les images utilisées.

## Exemples de modifications
  - **Modification des images en fonction des écrans** : Les images passent à 100% de largeur sur les écrans inférieurs à 768px pour une meilleure lisibilité.
   - **Texte** : Les titres et sous-titres s'ajustent pour offrir une meilleure lisibilité et hiérarchie visuelle sur mobile.

## Crédit
 Les images utilisées proviennent d'Unsplash et sont libres de droit.