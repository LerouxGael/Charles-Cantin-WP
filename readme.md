# Charles Cantin Photographie

Ceci est un exercice pour ma formation de développeur. 

## Prérequis

Ce site est un site WordPress, il est donc nécessaire de le déployer sur un serveur sur lequel a été installé PHP 8, ainsi qu'une base de donnée.

## Installation 

- installer Wordpress dans votre environnement.
- copier le contenu des dossiers wp-content/plugins et wp-content/themes du dépot git dans les dossiers correspondant sur votre environnement.
- connectez-vous à l'interface de gestion de base de donnée de votre environnement, localisez le fichier en .sql du dépot git, et importez son contenu dans votre base de donnée.
- localisez la table wp-options et modifiez l'url stocké dans les deux premières ligne, remplacez le par celui correspondant à votre environnement.
- Connectez-vous à l'interface d'administration de Wordpress et ajoutez l'extension Better Search Replace (de WP Engine).
- À l'aide de l'extension, cherchez et remplacez toutes les occurences de l'ancienne url par la nouvelle dans toutes les tables de la base de donnée.

## Modifications

- Pour ajouter des images à la page galerie, passez par l'extension Photo Gallery (ne pas oublier les tags pour le tri des photos).

- Pour modifier les headers ou les footers, utilisez l'extension Elementor Header & Footer Builder

- Pour modifier le contenu des pages Home, Contact et Validation, utiliser l'éditeur Elementor. Pour les autres pages l'éditeur de base suffit.


---------


Pour me contacter : lerouxgael@yahoo.fr