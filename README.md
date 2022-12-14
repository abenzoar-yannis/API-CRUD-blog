# API-CRUD-blog

API CRUD pour la gestion des articles pour le Blog de BK Yeslife

## Technologies utilisées

- [Node.js](http://nodejs.org)
- [Express](http://expressjs.com)
- [MongoDB-Atlas](https://www.mongodb.com/)

## Variables d'environnement

-[dotenv](https://www.npmjs.com/package/dotenv)
Avant de lancer ce projet, vous devrez ajouter les variables d'environnement suivantes dans un fichier .env (vérifier le typage des variables dans le fichier config/dotenvConfig.js)

- PORT (Configure le port d'utilisation)
- DB_USER (identifient de connexion MongoDB)
- DB_PASSWORD (password de connexion MongoDB)
- DB_HOST (nom du cluster MongoDB)
- DB_NAME (nom de la base de donnée MongoDB)
- SECRET_TOKEN (clé de codage du Token de jsonwebtoken)
- USER_ROLE (définir le nom/code du role)
- ADMIN_ROLE (définir le nom/code du role)

## Installation du backend

### Installer les dépendances

```bash
npm install
```

### Démarrer le serveur

Start :

```bash
node server
```

Dev :

```bash
nodemon server
```

[dotenv]: https://www.npmjs.com/package/dotenv
[jsonwebtoken]: https://www.npmjs.com/package/jsonwebtoken
[//]: # "order for gitfolio"
