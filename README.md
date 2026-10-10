# AutoLoc

Plateforme de gestion de location de véhicules multi-agences.
Projet réalisé dans le cadre de l'UP ASI (Architecture des Systèmes d'Information) à ESPRIT.

## Objectifs du projet

- Gérer le parc de véhicules de plusieurs agences
- Permettre aux clients de rechercher, réserver et louer un véhicule
- Suivre les contrats de location, les paiements et les retours de véhicules
- Offrir aux responsables d'agence des statistiques sur leur activité
- Exposer une API REST documentée (Swagger) et testée

## Acteurs identifiés

| Acteur | Rôle |
|---|---|
| Client | Recherche des véhicules, réserve, consulte l'historique de ses locations |
| Agent d'agence | Traite les réservations, remet et récupère les véhicules au guichet |
| Responsable d'agence | Supervise son agence, son parc de véhicules et ses statistiques |
| Administrateur | Gère les agences, les utilisateurs et la configuration globale |

## Premiers cas d'utilisation

- **Client :** s'inscrire, rechercher un véhicule disponible, réserver, annuler une réservation
- **Agent d'agence :** créer un contrat de location, enregistrer le retour d'un véhicule
- **Responsable d'agence :** gérer le parc de son agence, consulter les statistiques
- **Administrateur :** gérer les agences et les comptes utilisateurs

## Stack technique

- Java 17, Maven
- Spring Boot, Spring Data JPA, Spring MVC
- MySQL 8 (base `autoloc_db`)
- Lombok, springdoc-openapi (Swagger UI)
- JUnit 5, Mockito
- Git/GitHub, Postman, IntelliJ IDEA Ultimate

## Équipe

- Dhia Toumi
  
## Environnement de développement

Voir la preuve de l'environnement opérationnel : `docs/environnement.png`
