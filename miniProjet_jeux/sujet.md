---
title: "Mini projet en C++ : Création d'un jeu basique"  
author : "BTS CIEL Informatique et Réseaux"
date : 05/12/2023

# Conditions

## Organisation

* par groupe de 2 (ou 3 maximum)  
* 3 séances en classe  
* être en mesure d'expliquer chaque ligne du code et de justifier ses choix.

## Contraintes techniques

* Pas d'utilisation d'outils autres que de la documentation (IA interdite)  
* Vous vous efforcerez de décomposer votre programme en différentes fonctions.  
* Chaque membre du groupe doit programmer au moins une fonctionnalité du 
programme final et mettre son nom en commentaire pour l'identifier.  

# Sujets

## Jeu du Mölkky

Le mölkky est un jeu d'adresse inventé par l'entreprise finlandaise Lahden 
Paikka. Le principe du jeu est de faire tomber des quilles en bois à l'aide 
d'un lanceur appelé Mölkky.

Il y a 12 quilles numérotées de 1 à 12. Pour abattre les quilles, les joueurs 
lancent le Mölkky.  
Il y a deux façons de marquer des points :  
* Si un joueur fait tomber plusieurs quilles, il gagne autant de points 
que de quilles abattues.
* Si un joueur fait tomber une seule quille, il gagne autant de points 
que le nombre inscrit dessus (s'il ne fait tomber que la quille numérotée 
4, il inscrira 4 points).

L'équipe gagnante est la première qui arrive à totaliser exactement 50 
points.  
Si une équipe dépasse ce score, elle retombe à 25 points.  
Lorsqu'une quille a été abattue, on la redresse sur son pied, le numéro 
face à la zone de lancer, juste là où elle se trouve.

\vspace{15pt}
L'objectif de ce mini-projet va être de créer un programme permettant de 
compter les points au Mölkky au cours d'une partie.

**Niveau 0 :**   
Votre programme calcule le nombre de points lorsqu'une seule équipe joue, 
jusqu'à sa victoire. Les valeurs des quilles tombées étant saisies 
par l'utilisateur.  
**Niveau 1 :**  
Votre programme détermine aléatoirement les quilles tombées et calcule 
le nombre de points lors d'un match entre deux équipes, jusqu'à la victoire 
d'une équipe.  
**Niveau 2 :**  
Votre programme pourra gérer les matchs entre trois équipes.  
**Niveau 3 :**   
On implémentera une variante du jeu, où chaque équipe pourra effectuer 
jusqu'à 3 lancers à la suite avant de faire jouer l'équipe suivante.

\vspace{30pt}
## Zanzibar

* 2 joueurs et +
* 3 dés

Le premier joueur lance les dés :  

* s'il fait un as (1) il marque 100 points,  
* s'il fait un 6 il marque 60 points,  
* les autres faces du dé indiquant le nombre de points correspondant 
(2= 2 points, 3= 3 points, 4= 4 points, 5= 5 points).

On joue en un lancer de dés et on fait 3 tours.
Le gagnant est celui qui a le plus de points au bout des 3 tours.
L'objectif de ce mini-projet va être de créer un programme permettant de 
compter les points au Zanzibar au cours d'une partie.

**Niveau 0 :**   
Votre programme calcule le nombre de points lorsqu'un seul joueur joue, 
jusqu'à sa victoire. Les valeurs de dés sont saisies par l'utilisateur.  
**Niveau 1 :**  
Votre programme calcule le nombre de points lors d'un match entre deux joueurs, 
jusqu'à la victoire d'un des joueurs. Les valeurs de dés sont tirés 
aléatoirement.  
**Niveau 2 :**  
Votre programme pourra gérer les matchs entre trois joueurs.  

\vspace{30pt}
## Bataille navale

* 2 joueurs  
* 1 plateau à 2 tableaux

Tour à tour, les joueurs doivent trouver les positions des navires de 
l'autre joueur pour les couler.  
La partie est terminée quand tout les navires de l'adversaire sont coulés. 
Pour simplifier, un plateau de 10x10 cases pourra suffir avec dans ce cas 
1 bateau de 4, un autre de 3 et un bateau de 2.

**Niveau 0 :**   
Votre programme simule une partie en affichant le plateau de chaque joueur 
à tour de role sous la forme d'un tableau 2D . Les cases sont choisies 
par les deux joueurs et la fin de partie déterminée visuellement. Les 
navires sont positionnés dès le départ par le programme et ne peuvent 
être modifiés par les joueurs.  
**Niveau 1 :**  
Les navires sont placés par les joueurs.  
**Niveau 2 :**  
Un joueur joue contre l'ordinateur qui choisit aléatoirement ses tirs.  
\vspace{30pt}
