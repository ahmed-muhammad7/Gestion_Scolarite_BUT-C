🎓 Gestion de la Scolarité des Étudiants (Interpréteur de Commandes)

Ce projet est une implémentation d'un système de gestion de scolarité pour une formation de type BUT Informatique.Il a été réalisé dans le cadre de la **SAE S1.01** ("Implémentation d'un besoin client") en première année d'étude

L'objectif était de développer un interpréteur capable de lire des commandes, de gérer une base de données d'étudiants en mémoire et d'appliquer des règles de gestion complexes (moyennes, compensation, jurys)

## ⚠️ Contexte du projet (Disclaimer)

**Ce dépôt contient mon tout premier projet de développement en langage C.**

Le programme est **entièrement fonctionnel** et respecte le cahier des charges, mais il reflète mon niveau d'apprentissage à l'époque :
* ❌ **Pas de programmation modulaire :** Tout le code source réside dans un fichier unique (`SAE.c`) au lieu d'être séparé en fichiers `.h` et `.c`.
* ❌ **Factorisation limitée :** Certaines logiques pourraient être optimisées ou mieux découpées en fonctions.
* ✅ **Logique algorithmique valide :** Le système gère correctement les cas complexes demandés (RCUE, compensations, passage d'année).

Je le publie ici pour archiver ma progression en tant que développeur.

## 🚀 Fonctionnalités

**Gestion des étudiants :** Inscription (`INSCRIRE`), affichage de la liste (`ETUDIANTS`), démission et défaillance.
**Gestion des notes :** Saisie des notes (`NOTE`) pour 6 UE par semestre.
**Suivi du cursus :** Affichage détaillé du bulletin de notes et des codes de validation (`CURSUS`)
**Simulation de Jury :** Lancement des jurys de fin de semestre (`JURY`) avec calcul automatique des admissions (ADM), ajournements (AJ) et compensations (ADC/ADS)
**Statistiques :** Bilan annuel des promotions (`BILAN`).
