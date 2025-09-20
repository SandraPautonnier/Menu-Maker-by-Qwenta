# Projet professionnalisant Openclassrooms : Menu Maker by Qwenta - Application de création de menu pour les restaurants

Contexte fictif : 
Qwenta un leader de l’impression de supports professionnel veut se diversifier. 
Menu Maker répond à cet objectif : 
une application innovante destinée aux restaurateurs, leur permettant de créer, personnaliser et exporter leurs menus de manière simple et efficace :
- Offrir aux restaurateurs une interface intuitive et adapter à leurs besoins et préférences de personnalisation.
- Permettre l'exportation des menus sous forme de PDF et vers des plateformes comme Deliveroo et Instagram

## Objectif du projet :
- Planifier un projet de développement complet d'après les besoins clients.
- Entreprendre un système de veille technologique
- Rédiger les spécifications techniques
- Présentez la solution technique 

## Spécifications techniques  :
- Authentification : Utilisation de JWT pour une connexion sécurisé.
- Création de catégorie : Intégration de react-modal car React propose des modales performantes et accessibles.
- Création de menu : Intégration de l’API REST afin de Créer, Afficher, Modifier et Supprimer (Intégré également dans la fonctionnalité “Menu précédents”
- Style de menu : Mise en place de Redux afin de faciliter la gestion des états globaux.
- Exportation de menu : Utilisation de react-to-pdf, bibliothèque facilitant la création de PDF.
- Stockage des menus : Mise en place de AWS S3 pour stocker les PDF.
- Impression de menu : Intégration de windows.print(), car c’est simple à implémenter.
- Deliveroo et Instagram : Utilisation de OAuth pour gérer l’authentification sécurisé.
