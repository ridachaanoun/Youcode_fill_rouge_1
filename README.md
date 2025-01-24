**Cahier des Charges**  
**Projet : Clone de l'Intranet YouCode**  

## **1. Introduction**  
### **1.1 Présentation du Projet**  
L'objectif de ce projet est de développer un clone de la plateforme Intranet de YouCode, permettant aux administrateurs, enseignants et étudiants d'interagir efficacement. Cette plateforme servira de support pour la gestion des étudiants, des enseignants, des travaux à rendre et des annonces.

### **1.2 Acteurs du Système**  
- **Administrateur** : Gère les comptes utilisateurs (création, modification, suppression).  
- **Enseignant** : Assigne des travaux aux étudiants et leur attribue des points.  
- **Étudiant** : Accède aux travaux assignés et peut utiliser ses points pour obtenir des cadeaux.  

## **2. Spécifications Fonctionnelles**  
### **2.1 Authentification et Autorisation**  
- **Seule la connexion est autorisée** (pas d'inscription). Les comptes sont créés uniquement par l'administrateur.  
- **Système de rôles** : Administrateur, Enseignant, Étudiant.  

### **2.2 Gestion des Utilisateurs**  
- **Recherche d'utilisateurs** par nom.  
- **Filtrage des étudiants** par ville.  
- **Statuts étudiants** : PDE, Délégué.  
- **Catégorisation des étudiants** en groupes **A1 et A2**.  

### **2.3 Assignation de Travaux**  
- Les enseignants peuvent assigner des travaux aux étudiants.  
- Les étudiants peuvent consulter et soumettre leurs travaux.  

### **2.4 Système de Points et Récompenses**  
- Les enseignants peuvent attribuer des points aux étudiants.  
- Les étudiants peuvent utiliser leurs points pour obtenir des cadeaux dans l'application.  

### **2.5 Tableau de Bord et Notifications**  
- Tableau de bord personnalisé selon le rôle.  
- Les enseignants et administrateurs peuvent publier des annonces.  

## **3. Spécifications Techniques**  
- **Frontend** : Vue.js 3  
- **Backend** : PHP avec structure MVC  
- **Base de données** : MySQL  
- **Authentification** : Basée sur clé API  
- **Hébergement** : Déploiement en auto-hébergement ou cloud  

## **4. Contraintes et Sécurité**  
- Protection contre les attaques XSS et CSRF.  
- Optimisation des performances pour la gestion de plusieurs utilisateurs simultanés.  
- Conformité aux réglementations sur la protection des données.  

---  

Ce document servira de référence pour la conception et le développement du projet.

