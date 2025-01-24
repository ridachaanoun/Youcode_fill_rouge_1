**Cahier des Charges**  
**Projet : Clone de l'Intranet YouCode**  

## **1. Introduction**  
### **1.1 Présentation du Projet**  
Ce projet vise à créer un clone de l'Intranet YouCode. Il permettra aux administrateurs, enseignants et étudiants de communiquer et de gérer leurs activités facilement.  

### **1.2 Utilisateurs du Système**  
- **Administrateur** : Crée et gère les comptes utilisateurs.  
- **Enseignant** : Donne des devoirs aux étudiants et leur attribue des points.  
- **Étudiant** : Accède aux devoirs et peut échanger ses points contre des cadeaux.  

## **2. Fonctionnalités**  
### **2.1 Connexion et Accès**  
- **Connexion uniquement** (pas d'inscription). Seul l'administrateur crée les comptes.  
- **Rôles des utilisateurs** : Administrateur, Enseignant, Étudiant.  

### **2.2 Gestion des Utilisateurs**  
- **Rechercher un utilisateur** par nom.  
- **Filtrer les étudiants** par ville.  
- **Types d'étudiants** : PDE, Délégué.  
- **Groupes d'étudiants** : A1 et A2.  

### **2.3 Devoirs et Travaux**  
- Les enseignants peuvent donner des devoirs aux étudiants.  
- Les étudiants peuvent voir et rendre leurs devoirs.  

### **2.4 Points et Cadeaux**  
- Les enseignants peuvent attribuer des points aux étudiants.  
- Les étudiants peuvent utiliser leurs points pour obtenir des cadeaux.  

### **2.5 Tableau de Bord et Annonces**  
- Tableau de bord différent selon le rôle.  
- Les enseignants et administrateurs peuvent publier des annonces.  

## **3. Technologies**  
- **Frontend** : Vue.js 3  or Reack
- **Backend** : PHP (MVC)  
- **Base de données** : MySQL  
- **Sécurité** : Authentification avec clé API  
- **Hébergement** : Local ou Cloud  

## **4. Sécurité et Contraintes**  
- Protection contre les attaques XSS et CSRF.  
- Optimisation des performances pour plusieurs utilisateurs.  
- Respect des règles de protection des données.  

---  

Ce document décrit les bases du projet pour son développement.

