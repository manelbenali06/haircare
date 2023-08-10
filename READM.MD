### introduction du projet
-Ce référentiel contient un projet de vente de produits naturels développé avec symfony

1. Clonez ce référentiel sur votre machine locale :
git clone https://github.com/manelbenali06/haircare.git

## Installation
Installation des Dépendances via Composer:
          composer install
Mettre à jour votre fichier .env:
DATABASE_URL=mysql://db_user:db_pass@127.0.0.1:3306/db_name
Créer la base de donnée :
php bin/console doctrine:database:create
Appliquer la migration :
php bin/console doctrine:migrations:migrate

### Exécution
Lancez l'application Symfony en utilisant le serveur intégré :
sh
Copier le code
symfony server:start
Accédez à l'application dans votre navigateur à l'adresse http://localhost:8000 .

### Fonctionnalités
bénéficiant d'une gamme de produits naturels triés par catégories.
Ajoutez des produits à votre panier et passez une commande.
Gérez votre profil utilisateur et consultez l'historique des commandes.