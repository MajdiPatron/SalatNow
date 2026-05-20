# SalatNow — Horaires de Prière & Coran

SalatNow est une application web moderne et élégante permettant de consulter les horaires de prière musulmane en temps réel, d'écouter le Saint Coran et de recevoir des notifications d'Adhan.

## 🌟 Fonctionnalités

- **Horaires de Prière Précis** : Basés sur l'API Aladhan, avec plusieurs méthodes de calcul disponibles.
- **Configuration pour la Tunisie** : Paramétrée par défaut sur la méthode du **Ministère tunisien des Affaires religieuses** (UTC+01:00).
- **Géolocalisation & Recherche** : Détection automatique de votre position ou recherche par ville.
- **Lecteur du Saint Coran** : Écoutez les sourates avec des récitants renommés (Mishary Rashid Alafasy, Abdul Basit).
- **Notifications & Adhan** : Notifications push dans le navigateur à l'heure exacte de chaque prière avec l'appel à la prière (Adhan) sonore.
- **Compte à rebours dynamique** : Affiche le temps restant avant la prochaine prière.
- **Calendrier Mensuel** : Vue complète des horaires pour tout le mois en cours.
- **Mode Sombre/Clair** : Interface adaptative et moderne.

## 🚀 Technologies Utilisées

- **HTML5 / CSS3** : Design responsive avec variables CSS, Glassmorphism et animations.
- **JavaScript (ES6+)** : Logique de l'application, gestion du temps, API Fetch et Notifications.
- **API Aladhan** : Source de données pour les horaires de prière.
- **API AlQuran.cloud** : Source pour les données et l'audio du Saint Coran.

## 📂 Structure du Projet

- `index.html` : Fichier unique contenant la structure, le style et la logique de l'application.

## 🛠️ Installation & Utilisation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/SalatNow.git
   ```
2. Ouvrez le fichier `index.html` dans votre navigateur préféré.

> **Note** : Pour les notifications et la géolocalisation, il est recommandé d'utiliser un serveur local (ex: extension Live Server sur VS Code) car certains navigateurs bloquent ces fonctionnalités sur les fichiers locaux (`file://`).

## 📜 Crédits

- Données de prière : [Aladhan API](https://aladhan.com/prayer-times-api)
- Données du Coran : [AlQuran.cloud](https://alquran.cloud/api)
- Audio du Coran : [Islamic Network CDN](https://cdn.islamic.network)

---
*Développé avec ❤️ pour la communauté islamique al hamdu li alah .*
