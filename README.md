# DB-Searcher

# Description :
- L'outil DB Searcher est un script conçu pour effectuer des recherches avancées de texte au sein de fichiers situés dans un répertoire spécifique. Il permet aux utilisateurs de rechercher des termes spécifiques dans une base de données textuelle, offrant ainsi une manière rapide et efficace de trouver des informations précises dans de grands volumes de fichiers.

# Fonctionnalités principales :

## Recherche avancée :
- Vous pouvez rechercher un ou plusieurs termes à travers différents fichiers textuels. Le script utilise la commande findstr pour effectuer ces recherches, garantissant des résultats rapides et précis.

## Interface utilisateur :
- L'interface utilise des animations et des couleurs pour améliorer l'expérience utilisateur. Par exemple, la fonction slowType permet un affichage progressif du texte, rendant l'utilisation de l'outil plus interactive.

## Sauvegarde des résultats :
- Les résultats des recherches sont automatiquement sauvegardés dans un dossier nommé _save. Cela permet de conserver une trace des recherches effectuées et de pouvoir les consulter ultérieurement.

## Gestion des dépendances et dossiers :
- Lors de la première utilisation, le script vérifie et crée les dossiers nécessaires (_save pour les résultats et _db pour les fichiers de base de données) si ceux-ci n'existent pas déjà.

## Vérification et gestion de clé :
- Avant d'utiliser l'outil, une vérification de clé est effectuée pour s'assurer que seul un utilisateur autorisé puisse accéder à ses fonctionnalités. La clé est vérifiée via un canal Discord spécifique, garantissant ainsi la sécurité de l'accès.

## Utilisation :
- Le script est principalement utilisé en ligne de commande et nécessite Python. Il est destiné aux utilisateurs avancés qui ont besoin d'explorer des bases de données textuelles de manière rapide et sécurisée.

# Auteur :
- Ce script a été développé par @azvno.
