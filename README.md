## Gestion de Projet

Ce projet implémente un système de gestion de projet en express pour la gestion des employés, des tâches et des assignations. Le système permet de créer, lire, mettre à jour et supprimer des employés et des tâches, ainsi que d'assigner des tâches aux employés et de gérer ces assignations.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants :

- [ [Node.js](https://nodejs.org/fr)] (version 12 ou supérieure)
  (version 4.0 ou supérieure)

## Installation

Suivez ces étapes pour configurer le projet sur votre machine locale :

**Clonez le repository :**

```bash
git clone https://github.com/Mbaye01/TP45-Gestion-Projet-Express.git

```

**Accédez au dossier du projet :**

```bash
cd gestion-projet-express
```

**Installez les dépendances :**

```bash
npm install
```

```bash
npm install express
```

```bash
npm install body-parser
```

**Utilisation**

Pour démarrer l'application, exécutez la commande suivante :

```bash
npm start
```

[UML](./assets/UML_modele.png)

### Fonctionnalités

#### Gestion des Employés

Créer, lire, mettre à jour et supprimer des employés.

Attributs : id, nom, prenom, email, poste, dateEmbauche, statut.

#### Gestion des Tâches

Créer, lire, mettre à jour et supprimer des tâches.

Attributs : id, nom, description, dateDebut, dateFin, statut, priorite.

#### Gestion des Assignations

Assigner des tâches à des employés et retirer ces assignations.

Obtenir la liste des tâches assignées à un employé.

Obtenir la liste des employés assignés à une tâche.

Attributs : employe, tache, dateAssignation.

## Author

[Mbaye Abdellahi Kalidou](https://github.com/Mbaye01/TP45-Gestion-Projet-Express.git)
