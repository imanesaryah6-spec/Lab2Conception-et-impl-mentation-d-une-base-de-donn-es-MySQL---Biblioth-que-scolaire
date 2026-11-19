# Lab2Conception-et-impl-mentation-d-une-base-de-donn-es-MySQL---Biblioth-que-scolaire
# Lab: Gestion d'une Bibliothèque Scolaire (MySQL)
Ce projet contient la modélisation, la création, la sécurisation par contraintes et l'automatisation via des Triggers pour la base de données d'une bibliothèque scolaire.

📁 Structure du Projet
etudiant_backup.sql : Script d'exportation complet de la base de données (DDL, DML, Triggers).
README.md : Documentation du projet.
🛠️ Étapes de Réalisation
1. Initialisation de la Base de Données
Création de la base bibliotheque avec un encodage UTF-8 pour supporter les caractères accentués.

CREATE DATABASE IF NOT EXISTS bibliotheque
CHARACTER SET utf8mb4
COLLATE utf8mb4_unicode_ci;
USE bibliotheque;
