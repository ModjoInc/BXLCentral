# Projet : Pinterest
- Durée : 1 semaine
- Emplacement : [GitHub](https://github.com/) sur un repository intitulé "`projet-3-Pinterest`"  
- Le publier sur Heroku.

## Demande client
J'ai besoin d'un site participatif, permettant à tout le monde de partager des photos de manière anonyme. Le site à construire donnera simplement accès à un formulaire d'upload (téléchargement vers le serveur) et à une liste d'images gérée par [Masonry](https://masonry.desandro.com/).

J'aimerais que mon site ressemble à quelque chose comme ceci : ![Image exemple Pinterest](Pinterest.png)

## Ressources

- En PHP, la fonction [scandir()](http://php.net/manual/fr/function.scandir.php) permet de lire le contenu d'un dossier et récupérer son contenu sous forme de tableau.

## Objectifs principaux
1. formulaire d'upload en html sémantique
  - sécurité: limiter l'upload uniquement aux formats d'images les plus courants (jpg, jpeg, png, gif, WebP)
  - upload fonctionnel ([référence](https://www.w3schools.com/php/php_file_upload.asp))
1. afficher en html le contenu du dossier contenant les images
  - utiliser la fonction php `scandir()` pour "lire" le contenu du dossier
  - utiliser la librairie javascript "[Masonry](https://github.com/desandro/masonry)' pour contrôler le layout

## Objectifs supplémentaires
1. Permettre à l'utilisateur de modifier le cadrage de l'image (via la librairie php [simpleImage](https://github.com/claviska/SimpleImage))

## Pour commencer...
- Etude de la demande: as-tu tout compris? Pour le savoir, reformule la demande avec un(e) collègue et comparez votre compréhension mutuelle.
- Clarifie pour toi-même ce que devra faire ton script php, via de l'Unified Modelling Language (UML) ([example 1](http://astah.net/features/uml-features/uml-features-class.png), [example 2](http://msoe.us/taylor/tutorial/se1021/exceptionUML.png))
- Réalise un prototype papier de l'écran à construire.
- Crée un repository sur GitHub "`projet-3-Pinterest`"

#### Qu'est-ce que je sais déjà faire?
1. Créer un formulaire html
1. Ecrire du html
1. Utiliser un framework CSS
1. traiter d'un formulaire en php  

#### Qu'est-ce qui est nouveau ?
1. PHP: expérimenter avec l'upload
1. PHP: expérimenter avec scandir()
1. Associer une librairie javascript à du html


Bon amusement!