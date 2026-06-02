RELAIS IA V5 CLOUD

Cette version ajoute :
- synchronisation Firebase Firestore en temps réel
- création des interventions dans le cloud
- catégories Maintenance / Propreté / Réception / Direction
- création d'utilisateurs avec affectation de catégorie
- choix de l'utilisateur actif
- notifications internes dans l'application quand une tâche est créée pour sa catégorie
- mode démo local si Firebase n'est pas encore configuré

INSTALLATION RAPIDE
1. Ouvrir firebase-config.js
2. Coller les valeurs firebaseConfig de Firebase Console dans :
   apiKey, authDomain, projectId, storageBucket, messagingSenderId, appId
3. Mettre le dossier en ligne avec GitHub Pages / Netlify / Vercel.

IMPORTANT
Firebase fonctionne mal avec un simple fichier index.html ouvert localement sur Android.
Pour le vrai mode cloud, il faut héberger le dossier.

COLLECTIONS FIRESTORE UTILISÉES
- tasks
- users
- notifications

MODE TEST
Pour le prototype, Firestore peut rester en mode test.
Pour une vraie mise en production, il faudra ajouter une connexion et des règles de sécurité.
