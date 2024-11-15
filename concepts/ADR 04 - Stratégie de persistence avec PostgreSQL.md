> ADR de Michael Nygard
> https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions

# ADR 04 - Stratégie de persistence avec PostgreSQL

## Statut
Accepté

## Contexte
L'application nécessite une solution de base de données robuste, performante et facile à maintenir dans le cloud. Les besoins incluent :
- Haute disponibilité et scalabilité
- Gestion automatisée des sauvegardes
- Support des transactions ACID
- Facilité de maintenance et mises à jour

## Décision
Utiliser Cloud SQL PostgreSQL avec les caractéristiques suivantes :
- Configuration en haute disponibilité
- Utilisation du connection pooling
- Migrations gérées par Flyway
- Backup automatisés quotidiens

## Conséquences
Positives :
- Gestion automatisée par GCP
- Haute disponibilité native
- Backups et mises à jour simplifiés
- Scalabilité verticale et horizontale

Négatives :
- Coûts plus élevés que self-hosted
- Dépendance à GCP
- Limitations des personnalisations
- Latence réseau à considérer
