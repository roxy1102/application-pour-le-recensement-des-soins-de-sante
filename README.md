# Application de Recensement des Soins de Santé

Cette application permet de :
- Ajouter des patients et générer des rapports statistiques sur les conditions de santé.
- Rechercher des informations détaillées sur des maladies courantes (symptômes, prévention, traitement).
- Contacter l’équipe via un formulaire.

## Fonctionnalités

- **Ajout de patients** : Saisie du nom, genre, âge et condition.
- **Rapport dynamique** : Statistiques sur les conditions et la répartition par genre.
- **Recherche de condition** : Affichage des informations issues du fichier `health_analysis.json`.
- **Formulaire de contact** : Pour toute question ou demande d’information.

## Structure du projet

```
application pour le recensement des soins de santé/
│
├── index.html
├── health_contact.html
├── index.js
├── style.css
├── health_analysis.css
├── health_analysis.json
└── images/
```

## Installation & Lancement

1. **Cloner le projet**  
   ```bash
   git clone <lien-du-repo>
   ```

2. **Ouvrir dans VS Code**  
   Ouvre le dossier dans VS Code.

3. **Lancer un serveur local**  
   Pour charger le JSON correctement, utilise une extension comme [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) ou la commande :
   ```bash
   python -m http.server
   ```
   puis ouvre `http://localhost:8000/index.html` dans ton navigateur.

## Utilisation

- **Ajouter un patient** : Remplis le formulaire sur la page d’accueil et clique sur "Ajouter".
- **Voir le rapport** : Le rapport s’affiche automatiquement après chaque ajout.
- **Rechercher une condition** : Saisis le nom d’une maladie dans la barre de recherche et clique sur "Rechercher".
- **Contact** : Remplis le formulaire sur la page "Contactez-nous".

## Personnalisation

- Les maladies et leurs informations sont dans `health_analysis.json`.
- Les styles principaux sont dans `style.css`.

## Auteurs

- Projet réalisé dans le cadre du défi #100jours.

---

**Remarque** : Pour que les images s’affichent, place-les dans le dossier `images/` et vérifie que les chemins dans
