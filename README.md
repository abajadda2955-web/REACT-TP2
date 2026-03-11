# TP2 React – useState, événements, formulaires contrôlés et useEffect

## Objectif

Ce TP a pour objectif de mettre en pratique les notions suivantes :

- gestion de l’état local avec `useState`
- gestion des événements `onClick`, `onChange` et `onSubmit`
- formulaires contrôlés
- utilisation simple de `useEffect`
- respect du flux unidirectionnel des données

---
### Étape 1 : Préparer le projet React

Création du projet React et démarrage du serveur de développement.

<img width="651" height="593" alt="etape1" src="https://github.com/user-attachments/assets/8bf17e42-58e1-4533-b0da-b22d272916da" />



### Étape 2 : Composant Compteur avec useState

Création du composant Compteur.js qui affiche un compteur simple et permet
d’incrémenter sa valeur avec un bouton.

Concepts utilisés

useState

onClick


<img width="210" height="115" alt="rtape2" src="https://github.com/user-attachments/assets/a9e6d453-7675-4f5a-9aca-de9dbee19010" />


### Étape 3 : Composant MessageBouton avec événement onClick

Création du composant MessageBouton.js qui modifie le texte affiché après un clic sur un bouton.

Concepts utilisés

useState

onClick

<img width="313" height="187" alt="etape3" src="https://github.com/user-attachments/assets/069d56d7-b501-4352-9752-ace846e5663e" />



### Étape 4 : Formulaire contrôlé

Création du composant FormulaireNom.js avec un champ texte contrôlé par React, et affichage d’une alerte lors de la soumission.

Concepts utilisés

useState

onChange

onSubmit

formulaire contrôlé



<img width="552" height="339" alt="etape4" src="https://github.com/user-attachments/assets/f2372627-af49-4ee4-ba0a-6048619834eb" />


### Étape 5 : Compteur avec useEffect

Création du composant CompteurEffet.js qui utilise useEffect pour afficher la valeur du compteur dans la console à chaque mise à jour.

Concepts utilisés

useState

useEffect



<img width="603" height="440" alt="etape5" src="https://github.com/user-attachments/assets/fc53cde8-25ee-41b0-ae99-4e9ae378600a" />



### Étape 6 : Exercices pratiques
---
Exercice 1 : Affichage dynamique

Création d’un composant AffichageDynamique.js qui change le texte affiché à chaque clic.
---
Exercice 2 : Formulaire d’inscription

Création d’un composant FormulaireInscription.js avec deux champs :

prénom

email

Les valeurs sont affichées dans une alerte lors de la soumission.
---
Exercice 3 : Compteur avec effet personnalisé

Création d’un composant CompteurTitre.js qui :

affiche le nombre de clics

modifie le titre de l’onglet du navigateur avec document.title

<img width="759" height="588" alt="etape6" src="https://github.com/user-attachments/assets/71e2bffb-0495-4dc9-9365-744de3feaf13" />




Résultat final

L’application finale contient les composants suivants :

Compteur

MessageBouton

FormulaireNom

CompteurEffet

AffichageDynamique

FormulaireInscription

CompteurTitre

---

Technologies utilisées

React.js

JavaScript

HTML

CSS

Node.js

Create React App
