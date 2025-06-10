## Contexte

Un de vos collègues vient de se lancer sur un nouveau projet en Clean Architecture avec une approche DDD.  
Il vous propose de faire la **code review** de sa première *pull request (PR)*.  

Vous devez **mettre en évidence** :

- les normes qui ne sont pas respectées,
- les implémentations techniques qui ne suivent pas les principes de Clean Architecture et DDD.

## Glossaire

- **Real Estate** : Domaine de l'immobilier  
- **Property** : Bien à vendre  
- **Advisor** : Conseiller en charge de vendre le bien  

## Métier

Dans le contexte *Real Estate*, un **conseiller (Advisor)** peut entrer les informations d’un nouveau bien (**Property**) dans le système.

La fonctionnalité demandée est d’implémenter une **command Symfony** qui stocke un nouveau bien en prenant les arguments suivants :

- l’ID de la Property  
- l’ID de l’Advisor qui entre les informations de la Property  

## Structure des Dossiers