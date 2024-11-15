# Documentation Globale

## ADR (Architecture Decision Records)

### Concepts applicatifs

#### ADR 01 - [Choix de React comme framework frontend](concepts/ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md)
- **Titre**: [Choix de React comme framework frontend](concepts/ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#titre)
- **Statut**: [Accepté](concepts/ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#statut)
- **Décision**: [Utiliser React avec TypeScript comme framework frontend principal](concepts/ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#décision)
- **Conséquences**: [Large écosystème, typage fort, courbe d'apprentissage](concepts/ADR%2001%20-%20Choix%20de%20React%20comme%20framework%20frontend.md#conséquences)

#### ADR 02 - [Architecture microservices avec API Gateway](concepts/ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md)
- **Titre**: [Architecture microservices avec API Gateway](concepts/ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#titre)
- **Statut**: [Accepté](concepts/ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#statut)
- **Décision**: [Architecture microservices avec Apigee comme API Gateway](concepts/ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#décision)
- **Conséquences**: [Meilleure scalabilité, complexité accrue](concepts/ADR%2002%20-%20Architecture%20microservices%20avec%20API%20Gateway.md#conséquences)

### Concepts techniques

#### ADR 03 - [Choix de Spring Boot pour les backends](concepts/ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md)
- **Titre**: [Choix de Spring Boot pour les backends](concepts/ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#titre)
- **Statut**: [Accepté](concepts/ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#statut)
- **Décision**: [Utiliser Spring Boot 3.x avec Java 17](concepts/ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#décision)
- **Conséquences**: [Auto-configuration facilitée, consommation mémoire importante](concepts/ADR%2003%20-%20Choix%20de%20Spring%20Boot%20pour%20les%20backends.md#conséquences)

#### ADR 04 - [Stratégie de persistence avec PostgreSQL](concepts/ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md)
- **Titre**: [Stratégie de persistence avec PostgreSQL](concepts/ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#titre)
- **Statut**: [Accepté](concepts/ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#statut)
- **Décision**: [Utiliser Cloud SQL PostgreSQL avec connection pooling](concepts/ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#décision)
- **Conséquences**: [Gestion automatisée, coûts plus élevés](concepts/ADR%2004%20-%20Stratégie%20de%20persistence%20avec%20PostgreSQL.md#conséquences)

### Concepts migration

#### ADR 05 - [Stratégie de containerisation](concepts/ADR%2005%20-%20Stratégie%20de%20containerisation.md)
- **Titre**: [Stratégie de containerisation](concepts/ADR%2005%20-%20Stratégie%20de%20containerisation.md#titre)
- **Statut**: [Accepté](concepts/ADR%2005%20-%20Stratégie%20de%20containerisation.md#statut)
- **Décision**: [Docker avec multi-stage builds et Distroless](concepts/ADR%2005%20-%20Stratégie%20de%20containerisation.md#décision)
- **Conséquences**: [Images légères et sécurisées, debugging complexe](concepts/ADR%2005%20-%20Stratégie%20de%20containerisation.md#conséquences)

#### ADR 06 - [Pipeline CI/CD sur Google Cloud Build](concepts/ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md)
- **Titre**: [Pipeline CI/CD sur Google Cloud Build](concepts/ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#titre)
- **Statut**: [Accepté](concepts/ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#statut)
- **Décision**: [Implémenter CI/CD avec Cloud Build et Artifact Registry](concepts/ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#décision)
- **Conséquences**: [Automatisation complète, dépendance à GCP](concepts/ADR%2006%20-%20Pipeline%20CI%20CD%20sur%20Google%20Cloud%20Build.md#conséquences)

### Concepts exploitation

#### ADR 07 - [Monitoring et Observabilité](concepts/ADR%2007%20-%20Monitoring%20et%20Observabilité.md)
- **Titre**: [Monitoring et Observabilité](concepts/ADR%2007%20-%20Monitoring%20et%20Observabilité.md#titre)
- **Statut**: [Accepté](concepts/ADR%2007%20-%20Monitoring%20et%20Observabilité.md#statut)
- **Décision**: [Utiliser Cloud Operations Suite](concepts/ADR%2007%20-%20Monitoring%20et%20Observabilité.md#décision)
- **Conséquences**: [Vue unifiée du monitoring, coûts de rétention](concepts/ADR%2007%20-%20Monitoring%20et%20Observabilité.md#conséquences)

#### ADR 08 - [Stratégie de déploiement sur GKE](concepts/ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md)
- **Titre**: [Stratégie de déploiement sur GKE](concepts/ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#titre)
- **Statut**: [Accepté](concepts/ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#statut)
- **Décision**: [Utiliser Helm avec ArgoCD pour le GitOps](concepts/ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#décision)
- **Conséquences**: [Déploiements reproductibles, complexité des charts](concepts/ADR%2008%20-%20Stratégie%20de%20déploiement%20sur%20GKE.md#conséquences)

## Guides d'exploitation

### Procédures Techniques
- [Déploiement des services](guides/procedures-techniques.md#déploiement-des-services)
- [Mise à jour des composants](guides/procedures-techniques.md#mise-à-jour-des-composants)
- [Gestion des secrets](guides/procedures-techniques.md#gestion-des-secrets)

### Installation
- [Configuration GCP](guides/procedure-installation.md#configuration-gcp)
- [Déploiement initial](guides/procedure-installation.md#déploiement-initial)
- [Vérifications post-installation](guides/procedure-installation.md#vérifications-post-installation)

### Migration
- [Plan de migration](guides/procedure-migration.md#plan-de-migration)
- [Rollback](guides/procedure-migration.md#rollback)
- [Validation](guides/procedure-migration.md#validation)

### Observabilité
- [Configuration monitoring](guides/procedure-observabilite.md#configuration-monitoring)
- [Dashboards](guides/procedure-observabilite.md#dashboards)
- [Alertes](guides/procedure-observabilite.md#alertes)

### Sauvegarde
- [Stratégie de backup](guides/procedure-sauvegarde.md#stratégie-de-backup)
- [Restauration](guides/procedure-sauvegarde.md#restauration)
- [Tests de récupération](guides/procedure-sauvegarde.md#tests-de-récupération)

### Résilience
- [Gestion des pannes](guides/procedure-resilience.md#gestion-des-pannes)
- [Disaster Recovery](guides/procedure-resilience.md#disaster-recovery)
- [Tests de charge](guides/procedure-resilience.md#tests-de-charge)

## Nouveau Arrivant

### Configuration des accès
- [GCP Console](nouveau_arrivant/config_access.md#gcp-console)
- [Kubernetes](nouveau_arrivant/config_access.md#kubernetes)
- [Base de données](nouveau_arrivant/config_access.md#base-de-données)
- [Repositories git](nouveau_arrivant/config_access.md#repositories-git)

### Installation du poste
- [Prérequis](nouveau_arrivant/install_poste.md#prérequis)
- [SDK et outils](nouveau_arrivant/install_poste.md#sdk-et-outils)
- [Configuration IDE](nouveau_arrivant/install_poste.md#configuration-ide)
- [Configuration des accès](nouveau_arrivant/install_poste.md#configurer-ses-accès)

## Documentation de référence

### Architecture
- [Architecture Applicative](reference/architecture-applicative.md)
  - [Schéma d'Architecture Applicatif](reference/architecture-applicative.md#schéma-darchitecture-applicatif)
    - [Diagramme de déploiement GCP](reference/architecture-applicative.md#diagramme-de-déploiement-gcp)
    - [Flux de communication entre services](reference/architecture-applicative.md#flux-de-communication-entre-services)
  - [Composants Applicatifs](reference/architecture-applicative.md#composants-applicatifs)
    - [Frontend](reference/architecture-applicative.md#frontend)
    - [Backend Services](reference/architecture-applicative.md#backend-services)
    - [Base de données](reference/architecture-applicative.md#base-de-données)

- [Architecture Fonctionnelle](reference/architecture-fonctionnelle.md)
  - [Schéma d'Architecture Fonctionnelle](reference/architecture-fonctionnelle.md#schéma-darchitecture-fonctionnelle)
    - [Vue d'ensemble du système](reference/architecture-fonctionnelle.md#vue-densemble-du-système)
    - [Flux de données entre composants](reference/architecture-fonctionnelle.md#flux-de-données-entre-composants)
  - [Composants Fonctionnels](reference/architecture-fonctionnelle.md#composants-fonctionnels)
    - [Frontend Angular/React](reference/architecture-fonctionnelle.md#frontend-angularreact)
    - [API Gateway (Apigee)](reference/architecture-fonctionnelle.md#api-gateway-apigee)
    - [Microservices Backend](reference/architecture-fonctionnelle.md#microservices-backend)
    - [Base de données PostgreSQL](reference/architecture-fonctionnelle.md#base-de-données-postgresql)

- [Architecture Technique](reference/architecture-technique.md)
  - [Schéma d'Architecture Technique](reference/architecture-technique.md#schéma-darchitecture-technique)
    - [Infrastructure GCP](reference/architecture-technique.md#infrastructure-gcp)
    - [Réseau et sécurité](reference/architecture-technique.md#réseau-et-sécurité)
  - [Composants Techniques](reference/architecture-technique.md#composants-techniques)
    - [GKE Clusters](reference/architecture-technique.md#gke-clusters)
    - [Cloud SQL](reference/architecture-technique.md#cloud-sql)
    - [Apigee Configuration](reference/architecture-technique.md#apigee-configuration)
    - [Network Services](reference/architecture-technique.md#network-services)

### Exploitation
- [FinOps](reference/finops.md)
  - [Optimisation des coûts](reference/finops.md#optimisation-des-coûts)
  - [Monitoring des ressources](reference/finops.md#monitoring-des-ressources)
  - [Budgeting](reference/finops.md#budgeting)

- [Observabilité](reference/observabilite.md)
  - [Monitoring GCP](reference/observabilite.md#monitoring-gcp)
  - [Logging](reference/observabilite.md#logging)
  - [Alerting](reference/observabilite.md#alerting)
  - [Métriques clés](reference/observabilite.md#métriques-clés)

- [SLA](reference/sla.md)
  - [Objectifs de performance](reference/sla.md#objectifs-de-performance)
  - [Disponibilité](reference/sla.md#disponibilité)
  - [Temps de réponse](reference/sla.md#temps-de-réponse)

# End of document