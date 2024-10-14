# Scraping LinkedIn avec Make et API

## Description du projet

Ce projet permet de récupérer automatiquement les informations de profils LinkedIn à partir d'un formulaire Google. L'intégration utilise la plateforme Make et l'API **Fresh LinkedIn Profile Data** pour extraire les données d'un profil LinkedIn. Les informations obtenues sont ensuite traitées et transmises à une équipe désignée (Ressources Humaines ou Commerciale).

## Fonctionnalités

- Récupération des profils LinkedIn via un formulaire Google.
- Envoi d'une requête API pour extraire les informations du profil LinkedIn.
- Formatage des données et traitement avec ChatGPT pour obtenir un scoring.
- Envoi des résultats aux équipes désignées sous forme d'email HTML ou autre format enrichi.
- Bonus : Récupération des traits psychographiques via l'API **Humantic.ai**.

## Prérequis

- Un compte [Make](https://www.make.com/en) pour automatiser les workflows.
- Accès à l'API **Fresh LinkedIn Profile Data** via [RapidAPI](https://rapidapi.com/freshdata-freshdata-default/api/fresh-linkedin-profile-data).
- Un compte Google pour utiliser Google Forms.
- Une clé API pour l'API **Humantic.ai** (optionnelle).

## Étapes d'installation

1. **Google Form** : Créez un formulaire Google avec un champ pour recueillir les URL des profils LinkedIn.
2. **Configuration dans Make** :
   - Sélectionnez l'application Google Forms pour déclencher le workflow.
   - Ajoutez une action pour appeler l'API **Fresh LinkedIn Profile Data**.
   - Paramétrez la requête API avec l'URL LinkedIn soumise dans le formulaire.
   - Formatez la réponse reçue et envoyez-la à ChatGPT pour obtenir un scoring du profil.
3. **Envoi des résultats** :
   - Configurez un email HTML pour envoyer les résultats à l'équipe RH ou commerciale.
   - En option : Utilisez l'API **Humantic.ai** pour enrichir les données avec des traits psychographiques.

## Utilisation

Une fois le workflow mis en place, chaque soumission d'un profil LinkedIn via le formulaire Google déclenchera automatiquement la récupération des informations, leur traitement et leur envoi.

## APIs Utilisées

- **Fresh LinkedIn Profile Data** : API pour récupérer les informations des profils LinkedIn.
https://rapidapi.com/freshdata-freshdata-default/api/fresh-linkedin-profile-data


## Auteur

Ce projet a été réalisé par [Votre Nom].

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

https://rapidapi.com/freshdata-freshdata-default/api/fresh-linkedin-profile-data



![image](https://github.com/user-attachments/assets/ed62a57c-ac67-4d57-96db-0e9daa2cbbcf)
