# Sommaire des ADRs

## Concepts applicatifs

### ADR 01 - [Choix de React comme framework frontend](./ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md)
- **Titre**: [Choix de React comme framework frontend](./ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#titre)
- **Statut**: [Accepté](./ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#statut)
- **Décision**: [Utiliser React avec TypeScript comme framework frontend principal](./ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#décision)
- **Conséquences**: [Large écosystème, typage fort, courbe d'apprentissage](./ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#conséquences)

### ADR 02 - [Architecture microservices avec API Gateway](./ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md)
- **Titre**: [Architecture microservices avec API Gateway](./ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#titre)
- **Statut**: [Accepté](./ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#statut)
- **Décision**: [Architecture microservices avec Apigee comme API Gateway](./ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#décision)
- **Conséquences**: [Meilleure scalabilité, complexité accrue](./ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#conséquences)

## Concepts techniques

### ADR 03 - [Choix de Spring Boot pour les backends](./ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md)
- **Titre**: [Choix de Spring Boot pour les backends](./ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#titre)
- **Statut**: [Accepté](./ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#statut)
- **Décision**: [Utiliser Spring Boot 3.x avec Java 17](./ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#décision)
- **Conséquences**: [Auto-configuration facilitée, consommation mémoire importante](./ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#conséquences)

### ADR 04 - [Stratégie de persistence avec PostgreSQL](./ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md)
- **Titre**: [Stratégie de persistence avec PostgreSQL](./ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#titre)
- **Statut**: [Accepté](./ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#statut)
- **Décision**: [Utiliser Cloud SQL PostgreSQL avec connection pooling](./ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#décision)
- **Conséquences**: [Gestion automatisée, coûts plus élevés](./ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#conséquences)

## Concepts migration

### ADR 05 - [Stratégie de containerisation](./ADR%2005%20-%20Stratégie%20de%20containerisation.md)
- **Titre**: [Stratégie de containerisation](./ADR%2005%20-%20Stratégie%20de%20containerisation.md#titre)
- **Statut**: [Accepté](./ADR%2005%20-%20Stratégie%20de%20containerisation.md#statut)
- **Décision**: [Docker avec multi-stage builds et Distroless](./ADR%2005%20-%20Stratégie%20de%20containerisation.md#décision)
- **Conséquences**: [Images légères et sécurisées, debugging complexe](./ADR%2005%20-%20Stratégie%20de%20containerisation.md#conséquences)

### ADR 06 - [Pipeline CI/CD sur Google Cloud Build](./ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md)
- **Titre**: [Pipeline CI/CD sur Google Cloud Build](./ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#titre)
- **Statut**: [Accepté](./ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#statut)
- **Décision**: [Implémenter CI/CD avec Cloud Build et Artifact Registry](./ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#décision)
- **Conséquences**: [Automatisation complète, dépendance à GCP](./ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#conséquences)

## Concepts exploitation

### ADR 07 - [Monitoring et Observabilité](./ADR%2007%20-%20Monitoring%20et%20Observabilité.md)
- **Titre**: [Monitoring et Observabilité](./ADR%2007%20-%20Monitoring%20et%20Observabilité.md#titre)
- **Statut**: [Accepté](./ADR%2007%20-%20Monitoring%20et%20Observabilité.md#statut)
- **Décision**: [Utiliser Cloud Operations Suite](./ADR%2007%20-%20Monitoring%20et%20Observabilité.md#décision)
- **Conséquences**: [Vue unifiée du monitoring, coûts de rétention](./ADR%2007%20-%20Monitoring%20et%20Observabilité.md#conséquences)

### ADR 08 - [Stratégie de déploiement sur GKE](./ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md)
- **Titre**: [Stratégie de déploiement sur GKE](./ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#titre)
- **Statut**: [Accepté](./ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#statut)
- **Décision**: [Utiliser Helm avec ArgoCD pour le GitOps](./ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#décision)
- **Conséquences**: [Déploiements reproductibles, complexité des charts](./ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#conséquences)