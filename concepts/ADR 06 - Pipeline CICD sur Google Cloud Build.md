> ADR de Michael Nygard
> https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions

# ADR 06 - Pipeline CICD sur Google Cloud Build

## Statut
Accepté

## Contexte
Le projet nécessite une pipeline d'intégration et déploiement continu robuste et intégrée à GCP. Les besoins incluent :
- Automatisation complète des builds
- Gestion des environnements
- Tests automatisés
- Déploiements sécurisés

## Décision
Implémenter CI/CD avec Cloud Build :
- Integration avec GitHub/GitLab
- Utilisation d'Artifact Registry
- Tests automatisés à chaque PR
- Déploiements automatisés par env

## Conséquences
Positives :
- Intégration native avec GCP
- Automatisation complète
- Traçabilité des déploiements
- Gestion centralisée des artefacts

Négatives :
- Coûts des builds
- Dépendance à GCP
- Complexité des configurations
- Temps de build à optimiser
