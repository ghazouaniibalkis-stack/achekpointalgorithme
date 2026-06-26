# README – Algorithme d'analyse d'une phrase

## Description

Ce projet consiste à développer un algorithme qui lit une phrase **caractère par caractère** jusqu'à rencontrer un point (`.`). Au cours de cette lecture, l'algorithme calcule différentes informations sur la phrase à l'aide de trois variables compteurs.

## Objectifs

L'algorithme permet de déterminer :

* Le nombre total de caractères de la phrase.
* Le nombre total de mots (en supposant que les mots sont séparés par un seul espace).
* Le nombre total de voyelles présentes dans la phrase.

## Fonctionnalités

* Lecture de la phrase caractère par caractère.
* Arrêt de la lecture lorsqu'un point (`.`) est rencontré.
* Comptage du nombre de caractères.
* Comptage du nombre de mots en détectant les espaces.
* Comptage du nombre de voyelles (`a`, `e`, `i`, `o`, `u`, `y` si nécessaire).

## Contraintes

* Chaque caractère est traité individuellement.
* Le dernier caractère de la phrase est un point (`.`).
* L'algorithme utilise trois variables compteurs :

  * un compteur pour les caractères ;
  * un compteur pour les mots ;
  * un compteur pour les voyelles.

## Exemple

### Entrée

Bonjour tout le monde.

### Résultat

* Nombre de caractères : 22
* Nombre de mots : 4
* Nombre de voyelles : 8

## Principe de fonctionnement

1. Initialiser les trois compteurs à zéro.
2. Lire la phrase caractère par caractère.
3. Incrémenter le compteur des caractères à chaque caractère lu.
4. Si le caractère est un espace, incrémenter le compteur des mots.
5. Si le caractère est une voyelle, incrémenter le compteur des voyelles.
6. Arrêter la lecture lorsque le point (`.`) est rencontré.
7. Ajouter 1 au compteur des mots pour compter le dernier mot.
8. Afficher le nombre total de caractères, de mots et de voyelles.

## Auteur

**Nom :** balkis ghazouani**
