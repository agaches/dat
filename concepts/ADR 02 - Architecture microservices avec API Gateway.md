> ADR de Michael Nygard
> https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions

# ADR 02 - Architecture microservices avec API Gateway

## Statut
Accepté

## Contexte
L'application doit pouvoir évoluer de manière scalable et maintenir une séparation claire des responsabilités. Les besoins incluent :
- Gestion efficace des différentes fonctionnalités métier
- Capacité à scaler indépendamment les composants
- Sécurisation et monitoring centralisés des APIs
- Flexibilité pour les évolutions futures

## Décision
Nous avons choisi une architecture microservices avec Apigee comme API Gateway. Cela implique :
- Découpage en 3 microservices backend distincts
- Utilisation d'Apigee pour la gestion des APIs
- Communication inter-services via REST/gRPC
- Authentification et autorisation centralisées

## Conséquences
Positives :
- Meilleure scalabilité horizontale des services
- Isolation des domaines métier
- Gestion centralisée de la sécurité via Apigee
- Facilité d'évolution indépendante des services

Négatives :
- Complexité accrue de l'architecture distribuée
- Coûts d'infrastructure plus élevés
- Nécessité de gérer la cohérence des données
- Besoin de monitoring plus sophistiqué

