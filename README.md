<h1 align="center">🛒 Kanap JS</h1>

<p align="center">Site e-commerce frontend avec catalogue de canapés, panier et passage de commande.</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript ES6" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Express-4-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
</p>

## À propos

Kanap est un projet d'intégration JavaScript orienté e-commerce. Le frontend récupère les produits depuis une API Express et gère le catalogue, les fiches produits, le panier et la validation d'une commande.

## Fonctionnalités

- affichage dynamique du catalogue ;
- page produit avec sélection de quantité ;
- panier persistant dans le navigateur ;
- calcul du total et envoi d'une commande ;
- pages de confirmation et de retour utilisateur.

## Lancer en local

Prérequis : Node.js et npm.

    cd back
    npm install
    node server.js

L'API démarre généralement sur http://localhost:3000. Ouvrir ensuite index.html ou servir la racine avec un serveur statique local.

## API utilisée

| Méthode | Route | Usage |
| --- | --- | --- |
| GET | /api/products | Lister les produits |
| GET | /api/products/{id} | Consulter un produit |
| POST | /api/products/order | Envoyer une commande |

## Contexte

Projet de formation conservé comme exercice de JavaScript, DOM, appels HTTP et gestion d'état côté navigateur.

## Auteur

[Christopher Semard](https://github.com/christophersemard)
