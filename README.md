# POS-systhem
 systèmes de Point de Vente (POS) en laravel
	Le projet intitulé « Système de Point de Vente (POS) » s’inscrit dans le cadre de la digitalisation des transactions commerciales pour les petites et moyennes entreprises. Il s'agit d'une application web développée à l'aide du framework Laravel (PHP), qui vise à simplifier et automatiser les processus de vente, de gestion des produits et du suivi des clients.
	Cette plateforme permet aux utilisateurs (administrateurs) d'effectuer des opérations essentielles telles que :
	L'ajout, la modification et la suppression de produits
	La gestion des clients
	La réalisation de ventes via une interface intuitive
	Le suivi des commandes et des paiements
	La génération de rapports de vente (quotidiens et globaux)
	Grâce à son architecture modulaire et sa compatibilité avec des bases de données relationnelles comme MySQL, cette solution s’adapte facilement aux besoins des commerçants souhaitant moderniser leur gestion de caisse sans investissement matériel important.
	En somme, cette application offre une alternative économique, moderne et fiable aux systèmes de point de vente traditionnels.


#  Prérequis
PHP >= 8.0

Composer

MySQL

Node.js & npm (pour les assets frontend si nécessaire)

Git

XAMPP (optionnel pour test local rapide)

🚀 Installation du projet

1-Cloner le dépôt Git
git clone https://github.com/YoussefErraghay/POS-systh-m.git
cd POS-systh-m.git

2-Installer les dépendances PHP
composer install

3-Créer un fichier .env
cp .env.example .env

4-Générer la clé d'application
php artisan key:generate

5-Configurer la base de données
Ouvrir .env
Modifier ces lignes selon votre configuration MySQL :
makefile
DB_DATABASE=nom_de_votre_base
DB_USERNAME=root
DB_PASSWORD=

6-Exécuter les migrations et seeders
php artisan migrate --seed

7-Créer le lien vers le dossier de stockage
php artisan storage:link

8-Lancer le serveur
php artisan serve
Le projet sera disponible sur http://127.0.0.1:8000

👤 Accès administrateur (par défaut)
Email    : admin@example.com
Mot de passe : password
Vous pouvez modifier ces informations dans le DatabaseSeeder.

