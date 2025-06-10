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

## Technique

Le code a été conçu avec une **approche Clean Architecture** et selon les concepts liés au **DDD** (*Domain-Driven Design*), le but étant d’isoler et de protéger les règles métier.

> Il faut prendre en compte qu’il s’agit de code pour du **PHP 7.2**.  
> Les dépendances ainsi que certains fichiers sont **manquants volontairement** pour ne pas alourdir la code review.

## Restitution

Vous exposerez vos remarques sur la PR pendant **1h** à nos lead tech.  
Ce sera une base de discussion pour échanger plus en profondeur sur les problématiques rencontrées.

## Objectifs

Mettre en évidence :

- les soucis d’implémentation dans la PR ne respectant pas les grands principes de cette architecture,
- les erreurs ou améliorations possibles de conception,
- les erreurs liées aux normes de code,
- tout ce qui vous paraît anormal ou que vous auriez fait différemment.