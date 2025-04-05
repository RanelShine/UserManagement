# Gestion des Utilisateurs - CRUD avec Symfony 5.11.0

Ce projet est une application Symfony simple permettant de gérer des utilisateurs avec les fonctionnalités de Création, Lecture, Mise à jour et Suppression (CRUD). Il inclut également un système d'authentification (connexion et déconnexion).

## Fonctionnalités

- Liste des utilisateurs
- Ajout d'un nouvel utilisateur
- Visualisation des détails d'un utilisateur
- Modification d'un utilisateur
- Suppression d'un utilisateur
- Connexion / Déconnexion

## Prérequis

- PHP >= 7.4
- Composer
- Symfony 5.11.0
- Serveur local (ex: XAMPP, WAMP, MAMP ou Symfony CLI)
- Navigateur web

## Installation

1. **Cloner le projet**

   ```bash
  https://github.com/RanelShine/UserManagement.git
   cd UserManagement

2. **Installer les dependances**
   composer install

3. **Configurer l'environnement**
Copiez le fichier .env en .env.local et modifiez les paramètres de connexion à la base de données :

cp .env .env.local

4. **Lancer les migrations**
php bin/console doctrine:migrations:migrate

5. **Lancer les migrations**
php bin/console doctrine:migrations:migrate

6. **Lancer le serveur**
symfony server:start

7. **utilisation**
 Liste des utilisateurs : http://127.0.0.1:8000/user

Création d'un utilisateur : Lien disponible sur la page /user

Connexion : http://127.0.0.1:8000/login

Déconnexion : http://127.0.0.1:8000/logout

