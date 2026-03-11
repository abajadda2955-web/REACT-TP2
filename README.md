# 📘 TP2 React – Gestion de l’état et des événements


## 📖 Description

Ce TP a pour objectif de mettre en pratique les concepts fondamentaux de **React** liés à l’interactivité des applications :

* Gestion de l’état local avec **useState**
* Gestion des événements **onClick**, **onChange** et **onSubmit**
* Création de **formulaires contrôlés**
* Utilisation du hook **useEffect**
* Compréhension du **flux unidirectionnel des données**

L’application finale contient plusieurs composants interactifs permettant d’illustrer ces notions.

---

# ⚙️ Installation du projet

## 1️⃣ Création du projet

```bash
npx create-react-app tp-state
```

## 2️⃣ Accéder au dossier du projet

```bash
cd tp-state
```

## 3️⃣ Lancer le serveur de développement

```bash
npm start
```

L’application sera accessible à l’adresse :

```
http://localhost:3000
```

---

# 📁 Structure du projet

```
src/
│
├── App.js
├── Compteur.js
├── MessageBouton.js
├── FormulaireNom.js
├── CompteurEffet.js
├── AffichageDynamique.js
├── FormulaireInscription.js
├── CompteurTitre.js
└── index.js
```

---

# 🧩 Étapes du TP

## 🟢 Étape 1 : Préparation du projet

Création du projet React avec **Create React App** et démarrage du serveur de développement.

📷 Capture d’écran :

<img width="651" height="593" alt="etape1" src="https://github.com/user-attachments/assets/67274a98-3cec-4d77-8610-d34ecb74eb85" />

---

## 🟢 Étape 2 : Composant `Compteur`

Création d’un compteur simple utilisant **useState** pour gérer un état local.

Fonctionnalité :

* affichage du nombre de clics
* bouton permettant d’incrémenter le compteur

Concepts utilisés :

* `useState`
* `onClick`

📷 Capture d’écran :


<img width="210" height="115" alt="rtape2" src="https://github.com/user-attachments/assets/a2ba510b-6d2e-4796-8251-2897fceee152" />


---

## 🟢 Étape 3 : Composant `MessageBouton`

Création d’un bouton qui modifie dynamiquement le texte affiché.

Concepts utilisés :

* `useState`
* gestion des événements avec `onClick`

📷 Capture d’écran :

<img width="313" height="187" alt="etape3" src="https://github.com/user-attachments/assets/b98159f4-65a4-4f23-a018-ffd8bb00ed41" />


---

## 🟢 Étape 4 : Formulaire contrôlé

Création d’un formulaire avec un champ **Nom** contrôlé par React.

Fonctionnalité :

* récupération de la valeur saisie
* affichage dans une alerte lors de la soumission

Concepts utilisés :

* `useState`
* `onChange`
* `onSubmit`
* formulaires contrôlés

📷 Capture d’écran :

<img width="552" height="339" alt="etape4" src="https://github.com/user-attachments/assets/b1fcef55-4d61-4e7a-898f-8321b38e66b8" />


---

## 🟢 Étape 5 : Compteur avec `useEffect`

Création d’un compteur qui utilise **useEffect** pour afficher la valeur du compteur dans la console du navigateur à chaque modification.

Concepts utilisés :

* `useState`
* `useEffect`
* tableau de dépendances

📷 Capture d’écran :


<img width="603" height="440" alt="etape5" src="https://github.com/user-attachments/assets/e060d8ec-f8b2-4a9b-9c17-c74da49f933c" />

---

## 🟢 Étape 6 : Exercices pratiques

### Exercice 1 : Affichage dynamique

Création d’un composant qui modifie le texte affiché à chaque clic.

Exemple :

```
Premier clic
Deuxième clic
Troisième clic
```

---

### Exercice 2 : Formulaire d’inscription

Création d’un formulaire contrôlé contenant :

* un champ **Prénom**
* un champ **Email**

Les informations saisies sont affichées dans une **alerte** lors de la soumission.

---

### Exercice 3 : Compteur avec effet personnalisé

Création d’un compteur qui :

* affiche le nombre de clics
* met à jour le **titre de l’onglet du navigateur** avec `document.title`

📷 Capture d’écran :

<img width="759" height="588" alt="etape6" src="https://github.com/user-attachments/assets/eafb257a-04f8-412c-be4a-e9c082ee3d3a" />


---

# 🖥️ Résultat final

L’application finale contient plusieurs composants interactifs :

* Compteur simple
* Message dynamique
* Formulaire contrôlé
* Compteur avec effet
* Affichage dynamique
* Formulaire d’inscription
* Compteur modifiant le titre du navigateur


---

# 🛠️ Technologies utilisées

* ⚛️ React.js
* 🟨 JavaScript (ES6)
* 🌐 HTML / CSS
* 🟢 Node.js
* 📦 Create React App

---

# 👨‍💻 Auteur

TP réalisé dans le cadre d’un **travail pratique React**.

Étudiant : **BAJADDA ASMA**
