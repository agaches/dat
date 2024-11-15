> ADR de Michael Nygard
> https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions

# ADR 08 - Stratégie de déploiement sur GKE

## Statut
Accepté

## Contexte
Les déploiements doivent être fiables, reproductibles et suivre les principes GitOps. Les besoins incluent :
- Déploiements automatisés
- Gestion des configurations
- Rollbacks simples
- Maintenance facilitée

## Décision
Utiliser Helm avec ArgoCD :
- Templates Helm standardisés
- Déploiement GitOps avec ArgoCD
- Gestion des secrets avec Secret Manager
- Configuration par environnement

## Conséquences
Positives :
- Déploiements reproductibles
- Rollbacks facilités
- Configurations versionnées
- Automatisation complète

Négatives :
- Complexité des charts Helm
- Formation nécessaire
- Maintenance des templates
- Debuggage plus complexe
