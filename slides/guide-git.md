---
marp: true
theme: gaia
size: 16:9
paginate: true
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
header: 'Guide - git'
footer: Alexandre GIRARD - **Guide git**
---

![bg](https://images8.alphacoders.com/430/430944.jpg)

--- 

# **S**ource **C**ontrol **M**anagement

Outil qui permet de suivre les modifications apportées à une collection de fichiers.

Le terme **V**ersion **C**ontrol **S**ystem (VCS) est souvent utilisé de manière interchangeable. La différence est que le VCS n'est pas orienté développement logiciel, il peut être utilisé pour suivre les modifications apportées à n'importe quel type de fichier (texte, binaire, image, vidéo...).

---

# Objectifs d'un SCM

- Suivre les modifications apportées à un projet (quand, qui)
- Inclure un message descriptif pour chaque modification pour expliquer le pourquoi
- Permettre de revenir à une version antérieure du projet ou d'un fichier
- Travailler en parallèle sur différentes branches de développement (__feature__, __bugfix__...) par des personnes différentes sans affecter la branche principale (__main__, __develop__...)
- Marquer des versions stables du projet (__release__)

---

# Distributed Version Control System

- Système de gestion de version distribué
- Chaque utilisateur possède une copie complète de l'historique du projet
- Permet de travailler en local sans connexion à un serveur contrairement aux anciens systèmes de gestion de version centralisés (CVS, Subversion), qui nécessitent une connexion permanente au serveur

---
# **G**it - https://git-scm.com/

- Système de gestion de version distribué (DVCS)
- Créé par Linus Torvalds en 2005
- Rapide, simple, léger, performant, open source
- Utilisé par de nombreux projets open source et entreprises
- Services en ligne (GitHub, GitLab, Bitbucket, Azure DevOps) viennent ajouter des fonctionnalités (gestion de projet, CI/CD, wiki, issues, pull requests...)
- Intégration dans les IDE (VSCode, IntelliJ, Eclipse...)

---

# **G**it - terminologie

- **Repository** : répertoire de stockage des fichiers et de l'historique des modifications, c'est ici que **git** stocke toutes les informations nécessaires pour suivre les modifications apportées au projet, généralement dans un répertoire caché `.git`
- **Commit** : enregistrement d'une modification dans l'historique du projet
