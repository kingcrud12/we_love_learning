# WLL - We love learning

**WLL** est une plateforme de formation conçue pour offrir une expérience d'apprentissage confortable et sereine.

L'interface y est épurée et claire, l'apprenant n'est pas surchargé d'informations, il peut rapidement trouver des informations qui l'intéressent, suivre sa progression et avancer à son rythme.

Le formateur quant à lui, dispose d'une interface claire qui lui permet de créer et éditer des cours avec facilité et efficacité. Il a également accès aux différentes métriques sur chacune de ses formations : les temps de visionnage , conversion en visite achats etc

---

## Stack Technique

L'architecture repose sur une séparation stricte entre le client et le serveur pour garantir scalabilité et performance.

- **Frontend :** Angular 17+ & Tailwind CSS (Design System sur-mesure).
- **Backend :** Spring Boot 3+ (Java 17).
- **Base de données :** MySQL (Optimisée avec indexation sur les clés primaires).
- **Sécurité :** Stateless Auth via JWT (JSON Web Tokens).

## ROADMAP de réalisation de la plateforme

La réalisation de la plateforme s'est déclinée en différentes étapes :

- Conception
- Développement
- Déploiement

## Conception

La conception de WLL a pris la forme de : Modèle conceptuel, logique et physique de données (schéma de BDD)

- S'agissant du Modèle conceptuel de données (MCD) , l'objectif était de représenter les concepts métiers ainsi que les relations entre ses différents concepts.

- Le modèle logique est la traduction technique du MCD, les les propriétés des entités deviennent des attributs, ces attributs ont des types bien précis (VARCHAR, INT etc), les relations sont matérialisées par les clés étrangères, les règles métiers sont bien précisés.

- Le modèle physique de données prend en compte les contraintes du SGBD, nous travaillons avec une BDD mysql, la syntaxe , les règles d'insertion ont été utilisés dans le script de génération de la Base de données incluant des données de test.

Autres élements de la conception : les diagrammes de cas d'utilisation et de séquence.

- Les diagrammes de cas d'utilisation : nous a permis de bien représenter les cas d'utilisation attendu

- Les digrammes de séquence quant à eux, nous ont permis de représenter les flux prévus dans l'application ainsi que de montrer comment les différents services de l'app communiquent

Nous avons également mis en place des wireframes , maquettes , prototype en partant des diagrammes de cas d'utilisation

## Developpement

Une fois la conception terminée , nous sommes passés au développement. Nous l'avons divisé en deux phases :

**Phase 1 :** Développement backend (mise en place de l'API)
Durant cette phase nous nous sommes concentrés sur la mise en place de l'API

**Phase 2 :** Développement frontend (mise en place de l'interface utilisateur)
Durant cette phase nous nous sommes concentrés sur la mise en place de l'interface utilisateur de l'APP (deux interfaces devraient être développées, celle des formateurs et celle des apprenant )

## Déploiement

Nous avons opté pour l'hbergement et le déplooiement sur Hostinger via le présent repo
