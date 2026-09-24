# AutoLoc

Application de gestion de location de véhicules pour un réseau d'agences.

## Acteurs

| Acteur | Description |
|---|---|
| **Client** | Personne qui recherche, réserve et loue un véhicule. |
| **Agent d'agence** | Employé qui gère au quotidien les réservations, les départs et les retours de véhicules. |
| **Responsable d'agence** | Supervise une agence : flotte, tarifs, personnel et activité. |
| **Administrateur** | Gère la plateforme : comptes utilisateurs, agences et paramètres globaux. |

## Cas d'utilisation

### Client
- Créer un compte / s'authentifier
- Rechercher un véhicule disponible (dates, agence, catégorie)
- Consulter le détail et le tarif d'un véhicule
- Effectuer une réservation
- Modifier ou annuler une réservation
- Payer une réservation
- Consulter l'historique de ses locations

### Agent d'agence
- S'authentifier
- Consulter les réservations de l'agence
- Enregistrer une réservation pour un client (au comptoir)
- Effectuer le départ d'un véhicule (contrat, état des lieux)
- Effectuer le retour d'un véhicule (état des lieux, kilométrage, frais supplémentaires)
- Mettre à jour la disponibilité d'un véhicule (entretien, panne)

### Responsable d'agence
- S'authentifier
- Gérer la flotte de l'agence (ajouter, modifier, retirer un véhicule)
- Définir les tarifs et catégories de véhicules
- Gérer les agents de l'agence
- Consulter les statistiques de l'agence (taux d'occupation, chiffre d'affaires)

### Administrateur
- S'authentifier
- Gérer les agences (créer, modifier, fermer)
- Gérer les comptes utilisateurs et leurs rôles
- Configurer les paramètres globaux de la plateforme
- Consulter les statistiques globales

> Liste initiale issue de la Séance 1 — à compléter et affiner au fil du projet.
