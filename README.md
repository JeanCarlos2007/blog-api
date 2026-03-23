# blog-api
API backend pour gestion de blog

## Description

Ce projet consiste à développer une API backend permettant de gérer un blog.
L’API offre plusieurs fonctionnalités essentielles telles que la création, la consultation, la modification, la suppression et la recherche d’articles.

Ce projet a été réalisé dans le cadre d’un travail pratique en développement web afin de mettre en pratique les concepts du backend.

⸻

## Technologies utilisées
	•	Node.js
	•	Express.js
	•	SQLite
	•	Postman (pour les tests)

⸻

## Installation et lancement

    -Cloner le projet
        "bash"
        git clone https://github.com/user/blog-api.git
        cd blog-api

    2. installer les dépendances
        "bash"
        npm install

    3. Lancer le server
        "bash"
        node serveur.js

    4. Accéder à l'API
        ouvrir dans le navigateur :
        "code"
        http://localhost:3000

### Structure du projet


* Endpoints disponibles
 * Créer un article 
 . Méthode : POST
 . URL : /api/articles

"Exemple de données"
json
{
  "titre": "Mon premier article",
  "contenu": "Ceci est le contenu",
  "auteur": "Admin",
  "date": "2026-03-23",
  "categorie": "Tech",
  "tags": "nodejs,api"
}

* Récupérer tous les articles
	•	Méthode : GET
	•	URL : /api/articles

⸻

* Récupérer un article par ID
	•	Méthode : GET
	•	URL : /api/articles/:id

⸻

* Modifier un article
	•	Méthode : PUT
	•	URL : /api/articles/:id

⸻

* Supprimer un article
	•	Méthode : DELETE
	•	URL : /api/articles/:id

⸻

* Rechercher des articles
	•	Méthode : GET
	•	URL : /api/articles/search?query=motcle

⸻

## Tests

* Les tests ont été effectués avec Postman en vérifiant toutes les fonctionnalités de l’API :
	•	Création d’un article
	•	Lecture des articles
	•	Modification
	•	Suppression
	•	Recherche

⸻

* Améliorations possibles
	•	Ajouter un système d’authentification
	•	Créer une interface utilisateur (frontend)
	•	Ajouter une documentation avec Swagger
	•	Déployer l’API en ligne

⸻

## Conclusion

Cette API constitue une première implémentation d’un backend complet permettant de gérer un blog.
Elle permet de comprendre les bases du développement backend avec Node.js et Express.
:::
