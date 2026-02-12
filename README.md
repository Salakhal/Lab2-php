# 📘 LAB 2 — Programmation Orientée Objet & Modélisation Métier (PHP 7)

## 👩‍🎓 Cours
**Ingénierie Logicielle Web avec PHP 7 : Architecture Multicouche et Accès aux Données Sécurisé**

---

## 🎯 Objectifs pédagogiques

Ce laboratoire a pour objectif de construire un **modèle métier orienté objet** en PHP 7.

À la fin du LAB, nous savons :

- ✔ Définir des classes et instancier des objets  
- ✔ Appliquer l’encapsulation (attributs privés + getters/setters)  
- ✔ Implémenter des validations métier  
- ✔ Modéliser une relation objet–objet (Étudiant → Filière)  
- ✔ Définir un contrat CRUD via une interface Repository  
- ✔ Simuler une base de données avec un FakeRepository  
- ✔ Organiser le code avec namespaces et autoload (inspiration PSR-4)

---
 ## 📂 Structure du projet
 ```
PhpProject2/
│
├── public/
│     └── index.php
│
└── src/
      ├── Entity/
      │     ├── Filiere.php
      │     └── Etudiant.php
      │
      └── Repository/
            ├── RepositoryInterfacce.php
            └── FakeEtudianteRepository.php

```
## 🏗 Architecture

Le projet suit une organisation inspirée de PSR-4 :

-`Entity/` → Contient les objets métier

-`Repository/` → Contient la logique d’accès aux données

-`public/index.php` → Point d’entrée

## 🔄 Scénario CRUD testé
### ✔ Insertion

Deux étudiants insérés.

### ✔ Modification

Nom modifié via setter.

### ✔ Suppression

Un étudiant supprimé.

### ✔ Résultat attendu

<img width="383" height="314" alt="image" src="https://github.com/user-attachments/assets/9bae63d2-dfb4-4fdb-89c6-1462eb224aaa" />

## 👤 Auteur

* **École Normale Supérieure de Marrakech**
  
* **Réalisé par :** SALMA LAKHAL
  
* **Filière  :** CLE_INFO_S5
  
* **Année universitaire :** 2025/2026
  
* **Encadré par :** Pr. Mohamed LACHGAR
