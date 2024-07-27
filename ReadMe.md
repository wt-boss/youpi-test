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

   git clone https://github.com/wt-boss/youpi-test.git
   cd youpi-test-api
   composer install
   ```

2. **Configurer le `.env`**

3. **Générer la clé :**

   php artisan key:generate
   ```

4. **Faire les migrations :**

   php artisan migrate
   ```

5. **Démarrer le serveur :**

   
   php artisan serve
   ```

   L'API sera accessible à [http://localhost:8000](http://localhost:8000).

6. **Générer la documentation :**

   
   php artisan l5-swagger:generate
   ```

   La documentation sera accessible à [http://localhost:8000/api/documentation](http://localhost:8000/api/documentation).

### Frontend (React)

1. **Accéder au répertoire du frontend :**

   ``
   cd youpi-test-apk
   ```

2. **Installer les dépendances JavaScript :**

   
   npm install
   ```

3. **Démarrer l'application :**

   
   npm start
   ```
