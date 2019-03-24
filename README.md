# Bootstrap - One Million Lines
Vous allez reproduire une maquette relativement basique avec Bootstrap.

## Objectifs
* Mettre en pratique vos connaissances de Bootstrap de manière concrète.
* Découvrir de nouvelles fonctionnalités de Bootstrap.

## Consignes
Vous devez écrire le code HTML (index.html) et un peu de CSS (custom.css) pour but de reproduire
la charte graphique jointe à l’identique. Vous ne toucherez pas au code des autres fichiers. Tous
les fichiers nécessaires vous sont fournis. Vous n’avez ni besoin d’en ajouter, ni d’en supprimer.
Votre référence est le fichier [screenshot.png](https://github.com/simplon-roanne/bootstrap-onemillionlines/blob/master/screenshot.png).

## Spécifications minimales
Votre template HTML contiendra plusieurs parties dans l'ordre :
* une barre de navigation
* un jumbotron ayant pour id ‘home’, contenant la première partie et son contenu
* une div ayant pour id ‘who’, contenant la seconde partie et son contenu
* une div ayant pour id ‘get-involved’, contenant la troisième partie et son contenu
* un footer
* une div ayant pour id 'back-to-top’ et contenant la flèche permettant de remonter au jumbotron

Lorsque l’utilisateur clique sur le gros bouton ‘Learn more >>’ du jumbotron, une boite de dialogue
s’ouvrira avec une vidéo YouTube dedans [voir screenshot-modal.png](https://github.com/simplon-roanne/bootstrap-onemillionlines/blob/master/screenshot-modal.png). Indice : vous devrez
utiliser un concept de modal.

Vous utiliserez le système de grille de Bootstrap pour la partie ‘get-involved'.
Vous devrez certainement surcharger (== ré-écrire par dessus) l’une ou l’autre classe de
Bootstrap. Le fichier custom.css est mis à votre disposition à cet effet. Vous ne ferez **AUCUNE**
modification dans le fichier bootstrap.min.css.

Votre site doit être responsive. Vous devrez redimensionner/replacer certaines choses. Voir les
[screenshot-min1200.png](https://github.com/simplon-roanne/bootstrap-onemillionlines/blob/master/screenshot-min1200.png), [screenshot-min992.png](https://github.com/simplon-roanne/bootstrap-onemillionlines/blob/master/screenshot-min992.png) et [screenshot-min768.png](https://github.com/simplon-roanne/bootstrap-onemillionlines/blob/master/screenshot-min768.png)
Pour l’affichage sur smartphone (min-width: 768px), votre barre de navigation ne doit afficher que
le logo et une icône pour accéder au menu.

Pour afficher les icônes qui ne sont pas présentent dans les images, vous utiliserez Font Awesome
(http://fortawesome.github.io/Font-Awesome/) qui est déjà intégré au projet.

Conseil : servez-vous de la documentation de Bootstrap, elle est très complète et bourrée
d'exemples

## Spécifications bonus
Vous implémenterez un _smoothscroll_. Cet effet fait défiler la page "lentement" lorsque l’utilisateur
clique sur un lien du menu ou la flèche qui permet de remonter au début de la page. Votre code
JavaScript se trouvera dans le fichier smoothscroll.js lui même situé dans le dossier js.
Libre à vous de réaliser d’autres bonus. Soyez imaginatif !
