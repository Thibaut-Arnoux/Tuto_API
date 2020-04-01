# Création d'une API avec Node.js, Express et MongoDB

[Tutoriel](https://openclassrooms.com/fr/courses/6390246-passez-au-full-stack-avec-node-js-express-et-mongodb) : https://openclassrooms.com/fr/courses/6390246-passez-au-full-stack-avec-node-js-express-et-mongodb

> Création d'un dossier images à la racine car les dossiers vides ne sont pas pris en compte.
## Node Modules

- Nodemon
- Express
- Body-parser
- Mongoose
- mongoose-unique-validator
- bcrypt
- jsonwebtoken
- multer
- fs


## Partie 1

- Création de l'environnement de développement
- Création du serveur Node
- Création de l'application Express
- Création de route GET et POST et utilisation de Postman
- Configuration du CORS
- Utilisation du module body-parser

## Partie 2

- Utilisation de Mongoose pour la création de la base de données
- Stockage de la base de données sur MongoDB Atlas
- Création des routes CRUD
- Réalisation du quick n°2

## Partie 3

- Création des Utilisateurs
- Utilisation des JWT
- Cryptage des Password

## Partie 4

- Utilisation de multer pour l'upload d'image
- Modification de la route post
- Suppression de l'image sur le serveur lors de la mise à jour
- Suppression de l'image sur le serveur lors de la suppresion de l'objet

## Note

- L'opérateur spread ... est utilisé pour faire une copie de tous les éléments de req.body
- res => res.json()  
      <=>  
function(res){  
      return res.json();  
}  
- Update synthaxe
- Schéma de plusieurs objets avec MongoDB
