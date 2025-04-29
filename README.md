# Student Portal - Spring Boot Web Application

## 🎯 Objectif

Ce projet a pour but de développer une application web simple en **Spring Boot** permettant d'afficher dynamiquement les détails des étudiants à l’aide du moteur de template **Thymeleaf**. L'objectif principal est de comprendre le fonctionnement de l'affichage dynamique des données dans une application web Java moderne.

## 📝 Présentation du projet

L’application a été créée avec **Spring Initializr**, en intégrant les dépendances suivantes :

- **Spring Web** : pour développer des APIs et des contrôleurs web
- **Thymeleaf** : pour générer des vues HTML dynamiques
- **Spring Boot DevTools** : pour bénéficier du rechargement automatique en développement
- **Validation** : pour gérer la validation des formulaires côté serveur

Le projet est organisé selon l’architecture MVC (Modèle-Vue-Contrôleur) :

- Le **modèle `Student`** contient les attributs de base d’un étudiant (nom, email, etc.)
- Le **contrôleur `StudentController`** gère les requêtes et envoie les données à la vue
- La **vue `students.html`** est générée par Thymeleaf et affiche les données des étudiants de manière dynamique

L'application est démarrée avec la commande `./mvnw spring-boot:run` et est accessible sur `http://localhost:8080`.

## ✅ Compétences acquises

À travers ce lab, on apprend à :

- Créer et configurer un projet **Spring Boot**
- Utiliser **Thymeleaf** pour afficher du contenu dynamique
- Structurer un projet en suivant le modèle MVC
- Lier des objets Java à des vues HTML
- Intégrer la **validation des champs de formulaire**
- Utiliser les outils de développement comme **DevTools** pour une meilleure productivité

---

Projet réalisé dans le cadre du module 2 de l’apprentissage Spring Boot.
