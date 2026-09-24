Projet docker / web / BD / CI 
Réalisé par LucaFiglie, HugoSaulig et ValentinBlanc

Partie Web :

    Access / Refresh Token
    CORS (un front et un back) => pas de reverse proxy svp
    Middlewares
    Websocket
    Hash des passwords avec sel et poivre
    Cookies sécurisés pour les transferts de tokens
    REST
    HTTPS
    Pas de framework structurant (que du HTML / JS / CSS)

Partie BD :

    environ 5 tables

Partie déploiement :

    un seul fichier compose

Partie CI :

    Tests unitaires sur un module critique
    Lint et pre-commit
    Pousser automatiquement les images sur un container registry

Contraintes de fonctionnalités :

    Il faut au moins 2 rôles avec des accès différents (e.g. admin ou pas)
    Au moins une page dynamique (e.g. temps réel, animations, etc.)
