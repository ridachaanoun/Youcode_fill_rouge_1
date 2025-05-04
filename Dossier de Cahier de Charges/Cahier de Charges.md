# **Cahier des Charges**  
**Projet : Intranet Youcode**  

## **1. Introduction**  
### **1.1 Présentation du Projet**  
Ce projet vise à créer une plateforme intranet complète pour les établissements éducatifs. La plateforme servira d'espace centralisé permettant aux administrateurs, enseignants et étudiants de communiquer efficacement et de gérer leurs activités quotidiennes.

### **1.2 Utilisateurs du Système**  
- **Administrateur** : Responsable de la gestion globale du système et des utilisateurs.
- **Enseignant** : Chargé de l'encadrement pédagogique et du suivi des étudiants.
- **Étudiant** : Utilisateur principal bénéficiant des services éducatifs et de la plateforme de récompense.

## **2. Fonctionnalités Requises**

### **2.1 Authentification et Sécurité**
- **Connexion unique** : Seuls les administrateurs peuvent créer des comptes.
- **Gestion des rôles** : Trois niveaux d'accès distincts (administrateur, enseignant, étudiant).
- **Protection des données** : Sécurisation des informations personnelles et scolaires.

### **2.2 Gestion des Utilisateurs**
- **Profils complets** : Informations personnelles, académiques et professionnelles.
- **Organisation hiérarchique** : Administrateurs > Enseignants > Étudiants délégués > Étudiants.
- **Recherche et filtrage** : Possibilité de rechercher des utilisateurs par nom ou de filtrer par critères.
- **Types d'étudiants** : Différenciation entre étudiants réguliers, PDE, et délégués.
- **Niveaux éducatifs** : Classification des étudiants par groupes (A1, A2).

### **2.3 Organisation Pédagogique**
- **Gestion des classes** : Création et organisation des classes avec assignation d'enseignants.
- **Promotion et années scolaires** : Suivi des promotions d'étudiants au fil des années.
- **Suivi d'assiduité** : Enregistrement et gestion des absences des étudiants.
- **Historique de cursus** : Traçabilité du parcours académique des étudiants.

### **2.4 Système de Tâches et Évaluation**
- **Attribution de devoirs** : Les enseignants peuvent assigner des tâches aux étudiants.
- **Suivi des travaux** : Les étudiants peuvent visualiser
- **Évaluation continue** : Suivi des performances et accomplissements des étudiants.

### **2.5 Système de Récompense**
- **Attribution de points** : Les enseignants peuvent récompenser les étudiants par des points.
- **Tableau d'honneur** : Mise en avant des étudiants les plus performants.
- **Boutique de produits** : Les étudiants peuvent échanger leurs points contre des produits.

### **2.6 Communication**
- **Annonces globales** : Diffusion d'informations importantes à l'échelle de l'établissement.
- **Tableaux de bord personnalisés** : Interface adaptée selon le rôle de l'utilisateur.

## **3. Spécifications Techniques**

### **3.1 Architecture**
- **Frontend** : Vue.js 3 avec Pinia pour la gestion d'état et Axios pour les requêtes API.
- **Backend** : Laravel (PHP) avec architecture REST API.
- **Base de données** : PostgreSQL pour le stockage des données.
- **Authentification** : Système OAuth avec Laravel Passport.

### **3.2 Environnement de Déploiement**
- **Conteneurisation** : Docker pour faciliter le déploiement.
- **Services** : Application, base de données et interface d'administration.

### **3.3 Compatibilité**
- **Navigateurs** : Chrome, Firefox, Safari, Edge (versions récentes).
- **Responsive Design** : Adaptation aux différents formats d'écrans (desktop, tablette, mobile).

## **4. Contraintes et Exigences**

### **4.1 Sécurité**
- Protection contre les attaques courantes (XSS, CSRF, injection SQL).
- Gestion sécurisée des sessions et des tokens d'authentification.
- Chiffrement des données sensibles.

### **4.2 Performance**
- Temps de réponse rapide pour les opérations courantes.
- Capacité à gérer simultanément de nombreux utilisateurs.
- Optimisation pour minimiser la consommation de ressources.

### **4.3 Conformité**
- Respect des réglementations sur la protection des données personnelles.
- Accessibilité conforme aux standards WCAG 2.1.

## **5. Livrables Attendus**

### **5.1 Application**
- Code source complet (frontend et backend).
- Base de données initialisée avec données de démonstration.
- Documentation technique et manuel d'utilisation.

### **5.2 Documentation**
- Guide d'installation et de déploiement.
- Documentation API pour les intégrations futures.
- Manuel utilisateur adapté à chaque rôle.

---

Ce document décrit les bases du projet pour son développement.