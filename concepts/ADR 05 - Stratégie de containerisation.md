> ADR de Michael Nygard
> https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions

# ADR 05 - Stratégie de containerisation

## Statut
Accepté

## Contexte
Les microservices doivent être deployés de manière cohérente et sécurisée dans le cloud. Les besoins incluent :
- Reproductibilité des environnements
- Sécurité des images
- Optimisation des performances
- Facilité de déploiement

## Décision
Utiliser Docker avec les caractéristiques suivantes :
- Multi-stage builds pour l'optimisation
- Images base Distroless
- Configuration via ConfigMaps
- Standardisation des Dockerfiles

## Conséquences
Positives :
- Images légères et sécurisées
- Builds reproductibles
- Déploiements cohérents
- Isolation des dépendances

Négatives :
- Complexité des multi-stage builds
- Formation nécessaire sur Distroless
- Temps de build plus long
- Debugging plus complexe
