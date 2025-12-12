# Sushifast - Mathias Rakotomavo - Yannis Camelin

## 1 - Description
TP React et Vite qui consiste à créer une interface interactive nommée SushiFast, permettant d'afficher les menus en fonction de critère et scpécifications précises :

- Affichage de tous les menus (nom, pieces, image, prix).
- Présentation des saveurs de chaque menu.
- Liste des menus contenant les saveurs suivantes : avocat ou coriandre.
- Liste des aliments d'un menu donné
- Liste des menus ne contenant l'aliment : "California Saumon Avocat".
- Le prix total à payer pour une commande intégrant des menus dont le nombre de
pièces est inférieur à 13.
- Afficher le menu le plus cher et le menu le moins cher (nom, prix, pieces).

---

## 2 - Contraintes techniques

- L'application doit disposer d'un header et d'un footer
- L'utilisation d'un framework CSS est requise
- L'implémentation du routage est obligatoire
- L'utilisation du TypeScript est optionnelle
- Le choix du type composant est laissé à votre initiative (Fonctionnel ou Classe)
- Une qualité d'un code passe sa documentation
- Le travail final se rendra via un lien github, déposé sur e-learning.
- Un ReadMe sera associé à ce TP (sur github)

## 3 - Spécifications techniques
- **Framework :** React (Vite)
- **CSS :** Bootstrap + styles personnalisés (`accueil.css`)
- **Routage :** React Router
- **Données :** `boxes.json`


## 4 - Structure du projet

~~~
sushiFast/
 ├── public/
 │   ├── data/      
 │   └── img/
 │
 └── src/
     ├── components/
     │    ├──footer.css
     │    ├──footer.jsx
     │    ├──header.css
     │    └──header.jsx
     ├── pages/
     │      ├──accueil.css
     │      ├──accueil.jsx                  # Liste de tous les menus
     │      ├──aliments.jsx                 # Liste de tous les menus et en cliquant les aliments
     │      ├──avocatcoriandre.jsx          # Liste de tous les menus avec coriandre ou avocat
     │      ├──california.jsx               # Liste de tous les menus sans california
     │      ├──prix_pieces_inferieur13.jsx  # Liste de tous les menus avec moins ou egal a 13 pieces
     │      ├──prix.jsx                     # Liste de du menu le plus cher et moins cher
     │      └──saveur.jsx                   # Liste de tous les menus avec leurs saveurs
     ├── assets/
     │      └──react.svg
     ├── App.css
     ├── App.jsx
     ├── index.css          
     └── main.jsx
~~~
## 5 - Installation et lancement

### A - Cloner le dépôt

~~~
git clone https://github.com/YannisCam/TP_SushiFast
~~~

### B - Changer de directory
~~~
cd sushifast
~~~

### C - Installer

~~~
Dépendances:
npm install

Bootstrap :
npm install react-bootstrap bootstrap

React router:
npm install react-router-dom
~~~

### D - Lancement du projet

~~~
npm run dev
~~~

## 6 - Auteurs

Yannis Camelin & Mathias Rakotomavo




