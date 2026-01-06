EcoRide - Plateforme de covoiturage écologique

Application web de covoiturage éco-responsable développée dans le cadre du Titre Professionnel Développeur Web et Web Mobile

Description du projet

EcoRide est une plateforme permettant de mettre en relation des conducteurs et des passagers souhaitant partager leurs trajets en voiture, avec un accent particulier sur les véhicules électriques et l'écologie.

Technologies utilisées

# Front-end
- HTML5
- CSS3 (Bootstrap)
- JavaScript

# Back-end
- PHP 8.x
- PDO (PHP Data Objects)

# Base de données
- MySQL / MariaDB (relationnel)
- MongoDB (NoSQL - stockage des avis)

# Outils
- Git / GitHub
- Trello (gestion de projet)

Installation en local

# Prérequis
- PHP 8.0 ou supérieur
- MySQL / MariaDB
- MongoDB
- Serveur web (Apache/Nginx) ou XAMPP/WAMP

# Étapes d'installation

1. **Cloner le projet**
```bash
git clone https://github.com/TON-USERNAME/ecoride-covoiturage.git
cd ecoride-covoiturage
```

2. **Configurer la base de données MySQL**
```bash
# Créer la base de données
mysql -u root -p < database/create_db.sql

# Insérer les données de test
mysql -u root -p ecoride < database/insert_data.sql
```

3. **Configurer MongoDB**
```bash
# À compléter après installation
```

4. **Configurer les variables d'environnement**
```bash
# Copier le fichier de config
cp config/config.example.php config/config.php

# Éditer avec vos identifiants BDD
nano config/config.php
```

5. **Lancer le serveur**
```bash
# Avec PHP built-in server
php -S localhost:8000

# Ou via XAMPP/WAMP, placer le projet dans htdocs/www
```

6. **Accéder à l'application**
```
http://localhost:8000
```

## 📁 Structure du projet
```
ecoride-covoiturage/
│
├── assets/              # Ressources statiques
│   ├── css/
│   ├── js/
│   └── img/
│
├── config/              # Configuration
│   └── config.php
│
├── database/            # Scripts SQL
│   ├── create_db.sql
│   └── insert_data.sql
│
├── docs/                # Documentation
│   ├── charte-graphique.pdf
│   ├── maquettes/
│   ├── manuel-utilisateur.pdf
│   └── documentation-technique.pdf
│
├── includes/            # Fichiers PHP réutilisables
│   ├── header.php
│   ├── footer.php
│   └── functions.php
│
├── pages/               # Pages de l'application
│   ├── home.php
│   ├── login.php
│   └── ...
│
├── .gitignore
└── README.md
```

# Liens utiles

- **Application déployée :** [À compléter]
- **Trello (Kanban) :** [TON LIEN TRELLO]
- **Documentation :** Voir dossier `/docs`

# Identifiants de test

*(À compléter une fois l'application développée)*

# Administrateur
- Email : admin@ecoride.fr
- Mot de passe : AdminEcoRide2025!

# Employé
- Email : employe@ecoride.fr
- Mot de passe : EmployeTest2025!

# Utilisateur
- Email : user@ecoride.fr
- Mot de passe : UserTest2025!

#Fonctionnalités

- Inscription et connexion sécurisée
- Recherche de covoiturages par ville et date
- Filtres avancés (prix, durée, note, véhicule électrique)
- Création et gestion de trajets
- Système de crédits
- Historique des trajets
- Système d'avis et de notation
- Espace administrateur avec statistiques
- Espace employé pour modération

# Licence

Projet académique - TP DWWM 2025

# Auteur

**Surcin Kevin**  
Formation : Développeur Web et Web Mobile  
Session : Février 2025
