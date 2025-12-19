# Scolaris - Gestion des Effets Académiques ENSPD

## 📋 Description
**Scolaris** est une application web de gestion des effets académiques développée pour l'École Nationale Supérieure Polytechnique de Douala (ENSPD). Cette plateforme permet la gestion numérique des étudiants, des notes, et la génération de documents académiques.

## 🎯 Fonctionnalités principales

### 👥 Gestion des utilisateurs
- **Administrateur** : Accès complet à toutes les fonctionnalités
- **Étudiants** : Consultation des notes et téléchargement des documents
- Authentification unique avec rôles différenciés

### 📊 Tableau de bord administrateur
- Statistiques en temps réel (étudiants par filière/classe)
- Graphiques interactifs (Chart.js)
- Dernières inscriptions

### 🎓 Gestion des étudiants
- Inscription simplifiée avec génération automatique de comptes
- Liste complète des étudiants avec recherche
- Export des données au format CSV

### 📝 Gestion des notes
- Attribution des notes par filière, classe et semestre
- Calcul automatique des moyennes, mentions et crédits
- Validation stricte des données

### 📄 Documents académiques
- **Certificat de scolarité** : Document d'inscription
- **Relevé de notes** : Bulletin par semestre
- **Attestation de réussite** : Document de fin de cycle (5ème année)
- Génération PDF avec jsPDF
- Mise en page conforme aux standards ENSPD

### ⚙️ Paramètres
- Modification des identifiants administrateur
- Sauvegarde et restauration des données
- Paramètres système configurables

## 🛠️ Technologies utilisées

### Frontend
- **HTML5** : Structure sémantique
- **CSS3** : Styles personnalisés avec Bootstrap
- **JavaScript (ES6+)** : Logique métier
- **Bootstrap 5** : Framework CSS responsive
- **Font Awesome 6** : Icônes modernes
- **Chart.js** : Graphiques interactifs
- **jsPDF** : Génération de documents PDF

### Backend
- **Node.js** : Environnement d'exécution
- **Express.js** : Framework web
- **JSON** : Stockage des données
