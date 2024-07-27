# Application Task Management

Ce projet est une application de gestion de tâches construite avec React pour le frontend et Laravel pour l'API backend.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 18.13 ou supérieure)
- [Composer](https://getcomposer.org/) (pour Laravel)
- [PHP](https://www.php.net/) (version 8.1 ou supérieure)
- [MySQL](https://www.mysql.com/) ou un autre système de gestion de base de données compatible

## Installation

### Backend (Laravel)

1. **Cloner le dépôt Laravel :**

   ```bash
   git clone https://github.com/wt-boss/youpi-test.git
   cd youpi-test-api
   composer install
   configuerer le .env
   generez la cle
   faites les migrations
   php artisan serve
   L API sera accessible à http://localhost:8000.
   php artisan l5-swagger:generate 
   pour la documentation

Frontend (React)

cd youpi-test-apk

Installer les dépendances JavaScript :

npm install

npm start