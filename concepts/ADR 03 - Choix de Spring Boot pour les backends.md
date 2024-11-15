> ADR de Michael Nygard
> https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions


# ADR 03 - Choix de Spring Boot pour les backends

## Statut
Accepté

## Contexte
Les microservices backend nécessitent un framework Java moderne, performant et adapté au cloud. Les besoins incluent :
- Support des conteneurs et du cloud native
- Facilité de développement et de maintenance
- Bonnes performances et scalabilité
- Intégration native avec GCP

## Décision
Utiliser Spring Boot 3.x avec Java 17 pour tous les microservices backend :
- Configuration via Spring Cloud GCP
- Utilisation de Spring WebFlux pour la réactivité
- Integration de Spring Security
- Monitoring via Spring Actuator

## Conséquences
Positives :
- Auto-configuration facilitant le développement
- Support natif des images conteneurs optimisées
- Excellent support de GCP via Spring Cloud
- Écosystème riche de starters et plugins

Négatives :
- Consommation mémoire plus importante
- Temps de démarrage à optimiser
- Formation nécessaire sur les nouveautés Java 17