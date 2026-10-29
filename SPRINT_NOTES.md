# CampusConnect — TD3 : Sprint Planning et pilotage

## Sprint Goal

Permettre aux étudiants et aux professeurs de créer leur compte et de se connecter, afin d'accéder à leur espace personnel CampusConnect.

## Informations du Sprint

- Projet Jira : SCRUM — Mon équipe gestion de projets.
- Sprint : **Authentification** (29/10/2026 au 12/11/2026).
- Tableau : https://efrei-team-hbify06k.atlassian.net/jira/software/projects/SCRUM/boards/1
- Documentation Confluence : https://efrei-team-hbify06k.atlassian.net/wiki/spaces/MEGDP/pages/14385153
- Nature du travail GitHub : **documentation uniquement** ; aucun développement, test applicatif ou pipeline CI/CD n'est revendiqué.

## User Stories retenues

| Clé Jira | User Story | Estimation | Responsable |
| --- | --- | ---: | --- |
| [SCRUM-8](https://efrei-team-hbify06k.atlassian.net/browse/SCRUM-8) | Création de compte étudiant | 4 SP | Sacha |
| [SCRUM-9](https://efrei-team-hbify06k.atlassian.net/browse/SCRUM-9) | Connexion à l'espace étudiant | 4 SP | Baptiste Mendes |
| [SCRUM-6](https://efrei-team-hbify06k.atlassian.net/browse/SCRUM-6) | Création de compte professeur | 4 SP | Filip Petrovic |
| [SCRUM-16](https://efrei-team-hbify06k.atlassian.net/browse/SCRUM-16) | Connexion à l'espace professeur | 4 SP | David Kini |

**Total : 16 Story Points.** La tâche technique [SCRUM-24](https://efrei-team-hbify06k.atlassian.net/browse/SCRUM-24), attribuée à Chi ZHANG, est présente dans le Sprint et concerne la table des étudiants en base de données ; elle n'ajoute pas de Story Points au total ci-dessus.

## Bref compte rendu du Sprint Planning

1. Le groupe a retenu les quatre Stories liées à l'authentification car elles permettent un premier parcours cohérent pour deux types d'utilisateurs.
2. La création d'un compte précède la connexion. Les tâches documentaires de vérification des critères d'acceptation sont suivies en sous-tâches Jira, notamment SCRUM-34.
3. Les Stories sont estimées à quatre points chacune ; les tâches ont des responsables identifiés. L'objectif privilégie l'accès effectif à l'espace personnel plutôt qu'une simple liste d'actions.
4. Le Product Backlog conserve les fonctions de découverte et de participation aux événements ainsi que la messagerie pour un Sprint ultérieur.
5. Les blocages, les limites de travail en cours et les deux Daily Scrums sont décrits dans Confluence. Les scénarios simulés restent explicitement distincts des résultats réellement observés.

## Traçabilité Jira–GitHub

- Branche documentaire : `docs/SCRUM-8-sprint-notes`.
- Commit documentaire : mention de `SCRUM-8`.
- Pull Request : à créer dans GitHub puis à lier manuellement à SCRUM-8, sauf présence d'une intégration GitHub for Jira active.
- Un lien manuel dans un ticket Jira n'entraîne pas automatiquement un changement de statut du ticket.

Ce fichier est un livrable documentaire TD3. Il ne constitue pas une preuve que les fonctionnalités ont été développées ou testées.
