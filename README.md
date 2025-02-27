# 📝 Peoples Post - Test Technique 

Bienvenue dans ce test technique pour le poste de **Développeur Senior** chez **Peoples Post**.  
Ce test vise à évaluer vos compétences en **React, Node.js** et **choix libre** pour la base de données, ainsi que votre capacité à structurer un projet propre et maintenable.  

---

## 🚀 Objectif  

Développer une **application ToDoList** en **React (TypeScript)** avec une API en **Node.js** et une base de données **choix libre**.  

---

## 🎯 Fonctionnalités  

### 📌 Chaque tâche doit contenir :  
- Un **titre**  
- Une **description**  
- Une **priorité** (ex. : basse, moyenne, haute)  
- Un **état** (ex. : à faire, en cours, terminé)  
- Une **date d’échéance**  

### 🔧 Vous devez implémenter :  
✅ **CRUD des tâches** (Créer, Modifier, Supprimer)

✅ **Filtres** :  
  - Par **priorité**  
  - Par **état**  
  - Par **date d’échéance**
    
✅ **Recherche** :  
  - Par **titre**  
  - Par **description**  

---

## 🐳 Dockerisation  

Le projet doit être entièrement **dockerisé** avec **Docker** et **Docker Compose** pour faciliter son déploiement.  

### 🏗️ Exigences  
- Un `Dockerfile` pour le **frontend**  
- Un `Dockerfile` pour le **backend**
- Un `Dockerfile` pour la **base de donnée**  
- Un fichier `docker-compose.yml` pour orchestrer **frontend, backend et votre base de donnée**

> ⚠️ Vous devez fournir un fichier docker-compose.yml adapté à la base de données choisie.

---

## 🏆 Bonus (Optionnel mais apprécié)  

🔥 **Améliorations UI/UX**  
- Ajoutez des animations (ex. : transitions fluides, feedback visuel lors des actions).  
- Mode **Dark/Light** pour une meilleure accessibilité.  

🔄 **Optimisation des performances**  
- Implémentez un **lazy loading** des tâches.  
- Utilisez **React Query** ou **Redux Toolkit Query** pour la gestion des appels API.  

🔐 **Authentification & Sécurité**  
- Ajoutez une **authentification JWT** pour permettre à chaque utilisateur d’avoir sa propre liste de tâches.  
- Sécurisez les routes avec un middleware d’authentification côté **backend**.  

📊 **Statistiques & Dashboard**  
- Ajoutez un tableau de bord montrant le nombre de tâches **complétées**, **en cours** et **à faire**.  
- Affichez des graphiques interactifs avec **Recharts** ou **Chart.js**.  

📅 **Notifications & Rappels**  
- Implémentez un **système de notifications** pour rappeler les tâches proches de l’échéance.  
- Ajoutez un envoi d’email de rappel avec **Nodemailer**.  

💾 **Stockage & Sauvegarde**  
- Permettez aux utilisateurs d’**exporter** et d’**importer** leurs tâches au format JSON ou CSV.  

---

## 🛠️ Stack Technique  

- **Frontend** : React, TypeScript  
- **Backend** : Node.js, Express  
- **Base de données** :  Libre choix (**MongoDB, PostgreSQL...**)  
- **Style** : Libre choix (**Tailwind, MUI...**)  

---

## 🎨 UI / UX  

L'interface doit être :  
- **Agréable à utiliser**  
- **Intuitive et ergonomique**  

---

## 📏 Exigences Techniques  

- Code **propre, structuré et lisible**  
- Utilisation des **bonnes pratiques** (découpage en composants, architecture API claire...)  
- Un **Git propre** avec un historique bien organisé  
- Projet hébergé sur **GitHub**  

---

## 📝 Critères d'évaluation  

| Critère                | Description |
|------------------------|------------|
| **Fonctionnalités**    | Implémentation des exigences demandées |
| **Qualité du code**    | Clarté, maintenabilité, bonnes pratiques |
| **Compréhension**      | Pertinence des choix techniques |
| **Organisation**       | Structure du projet et gestion de Git |

---

## 📦 Installation du projet avec Docker  

### 1️⃣ Installer Docker et Docker Compose 
   [Téléchargez Docker](https://www.docker.com/get-started) si ce n’est pas déjà fait.

### 2️⃣ Cloner le projet
   ```bash
   git clone https://github.com/votre-repo.git
   cd votre-repo
   ```

### 3️⃣ Construire et lancer les conteneurs
   ```bash
   docker-compose up --build -d
   ```
> `-d` exécute les conteneurs en arrière-plan.

### 4️⃣ Vérifier que les conteneurs tournent
   ```bash
   docker ps
   ```
Vous devriez voir au moins trois conteneurs en cours d'exécution :

✅ **Frontend**(React)

✅ **Backend**(Node.js, Express)

✅ **Base de données**(selon votre choix)

### 5️⃣ Accéder à l’application
- Frontend : `http://localhost:3000`
- Backend : `http://localhost:5000`
- Base de données : Vérifiez l’URL selon votre choix (MongoDB, PostgreSQL, MySQL...)

### 4️⃣ Arrêter les conteneurs 
   ```bash
   docker-compose down
   ```
Cela arrête et supprime tous les conteneurs liés au projet.

## 📤 Méthode de rendu  

Une fois le projet terminé :  

1️⃣ **Hébergez votre code sur GitHub** en gardant un historique Git **propre et structuré**.  

2️⃣ **Assurez-vous que votre README est clair**, avec les instructions d’installation et d’utilisation.  

3️⃣ **Fournissez-nous l’accès à votre dépôt** en partageant le lien.  

4️⃣ **Ajoutez éventuellement une courte documentation** (Postman, Swagger, ou notes techniques).  

> 📌 **Bonus** : Si vous hébergez votre application sur une plateforme comme **Vercel, Netlify, ou Render**, ajoutez le lien déployé !  
