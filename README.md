📌 Employee Floor Planner – Workplace Map Manager

Employee Floor Planner est une application web interactive permettant de gérer, organiser et répartir les employés sur un plan d’étage composé de plusieurs zones. L’interface est fluide, claire et responsive, avec des règles d’accès strictes basées sur les rôles pour garantir une organisation professionnelle et cohérente.

✨ Fonctionnalités principales

➕ Ajout d’employés via une modale :

Nom, rôle, email, téléphone

Photo de profil

Expériences professionnelles

📋 Liste dynamique des employés non assignés

🗺️ Déplacement des employés vers 6 zones du bâtiment

🔒 Règles d’accès automatiques :

Réception → Réceptionnistes

Salle des serveurs → Techniciens IT

Sécurité → Agents de sécurité

Manager → accès total

Nettoyage → toutes zones sauf Archives

❌ Suppression / retrait via bouton X

👤 Profil détaillé de chaque employé

🔍 Recherche par nom ou rôle

📱 Responsive pour desktop, tablette, mobile

💾 LocalStorage (optionnel)

📝 Logs internes (optionnel)

📁 Structure du projet

📁 Workplace-Map-Manager

 ├── index.html
 ├── styles/
 │    ├── style.css
 │    └── responsive.css
 ├── scripts/
 │    ├── app.js
 │    ├── zones.js
 │    └── employees.js
 ├── assets/
 │    ├── images/
 │    └── icons/
 └── README.md
🧰 Technologies utilisées

HTML5 (Structure sémantique)

CSS3 (Flexbox, Grid, Media Queries)

JavaScript Vanilla (Logique + DOM)

LocalStorage (optionnel)

Git / GitHub (versionnement & déploiement)

📱 Responsive Design

Adapté à :

💻 Desktop : +1280px

🖥️ Laptop : 1024–1279px

📱 Tablet : 768–1023px

📲 Mobile : –767px

Tests effectués en portrait & paysage.

🧪 Tests & Validation

✔ Validé via W3C HTML Validator

✔ Vérification CSS

✔ Tests des règles d’accès

✔ Tests manuels :

Ajout / suppression

Modales (ouverture/fermeture)

Déplacements

Responsiveness

🌐 Navigateurs testés : Chrome, Firefox, Edge

🔧 Installation

Cloner le dépôt :

git clone https://github.com/ezraidimariam/Workplace-Map-Manager.git

Ouvrir index.html dans votre navigateur

L'application fonctionne immédiatement (aucune dépendance)

🌐 Déploiement

Compatible :

GitHub Pages

Netlify

📊 Améliorations futures

Mode Admin

Drag & Drop

Exportation des configurations

Authentification

Gestion multi-étages

API externe
