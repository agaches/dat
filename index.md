# Documentation Globale

## ADR (Architecture Decision Records)

### Concepts applicatifs

#### [ADR 1](adr/adr01.md)
- **Titre**: [Titre](adr/adr01.md#titre)
- **Statut**: [Statut](adr/adr01.md#statut)
- **Décision**: [Décision](adr/adr01.md#décision)
- **Conséquences**: [Conséquences](adr/adr01.md#conséquences)

#### [ADR 2](adr/adr02.md)
- **Titre**: [Titre](adr/adr02.md#titre)
- **Statut**: [Statut](adr/adr02.md#statut)
- **Décision**: [Décision](adr/adr02.md#décision)
- **Conséquences**: [Conséquences](adr/adr02.md#conséquences)

### Concepts techniques

#### [ADR 3](adr/adr03.md)
- **Titre**: [Titre](adr/adr03.md#titre)
- **Statut**: [Statut](adr/adr03.md#statut)
- **Décision**: [Décision](adr/adr03.md#décision)
- **Conséquences**: [Conséquences](adr/adr03.md#conséquences)

#### [ADR 4](adr/adr04.md)
- **Titre**: [Titre](adr/adr04.md#titre)
- **Statut**: [Statut](adr/adr04.md#statut)
- **Décision**: [Décision](adr/adr04.md#décision)
- **Conséquences**: [Conséquences](adr/adr04.md#conséquences)

### Concepts migration

#### [ADR 5](adr/adr05.md)
- **Titre**: [Titre](adr/adr05.md#titre)
- **Statut**: [Statut](adr/adr05.md#statut)
- **Décision**: [Décision](adr/adr05.md#décision)
- **Conséquences**: [Conséquences](adr/adr05.md#conséquences)

#### [ADR 6](adr/adr06.md)
- **Titre**: [Titre](adr/adr06.md#titre)
- **Statut**: [Statut](adr/adr06.md#statut)
- **Décision**: [Décision](adr/adr06.md#décision)
- **Conséquences**: [Conséquences](adr/adr06.md#conséquences)

### Concepts exploitation

#### [ADR 7](adr/adr07.md)
- **Titre**: [Titre](adr/adr07.md#titre)
- **Statut**: [Statut](adr/adr07.md#statut)
- **Décision**: [Décision](adr/adr07.md#décision)
- **Conséquences**: [Conséquences](adr/adr07.md#conséquences)

#### [ADR 8](adr/adr08.md)
- **Titre**: [Titre](adr/adr08.md#titre)
- **Statut**: [Statut](adr/adr08.md#statut)
- **Décision**: [Décision](adr/adr08.md#décision)
- **Conséquences**: [Conséquences](adr/adr08.md#conséquences)

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