# Déclaration de Travail d’Architecture (Architecture Statement of Work)
## Projet : Foosus – Plateforme d’Alimentation Durable

---

## 1. Contexte du projet

**Foosus** est une startup en pleine croissance dans le secteur de l’alimentation durable. Elle vise à rapprocher les consommateurs urbains des producteurs locaux via une application mobile géolocalisée.  
Cependant, la croissance rapide et les choix technologiques initiaux ont généré une **dette technique importante**, un manque de cohérence dans l’architecture applicative, et une complexité accrue dans l’ajout de nouvelles fonctionnalités.  

Pour répondre aux besoins d’évolutivité, de fiabilité et d’innovation, la direction de Foosus initie une mission d’architecture d’entreprise structurée autour du cadre **TOGAF**.


---

## 2. Objectifs de l’architecture

- Fournir une **vision d’architecture cible** cohérente avec les ambitions stratégiques de Foosus.
- Définir une **architecture modulaire, évolutive, sécurisée et interopérable**.
- Réduire la dette technique en proposant une **refonte raisonnée et itérative** des composants existants.
- Accélérer les cycles d’innovation en favorisant une architecture **orientée services** et découplée.
- Aligner les initiatives techniques avec les besoins des métiers et de l’expérience utilisateur.

---

## 3. Périmètre de l’architecture

### Inclus dans le périmètre :
- L’application mobile et son backend (actuellement monolithique)
- Les API d’exposition et de consommation de données (catalogue, recherche, profils…)
- Le système de géolocalisation et de matching producteur/consommateur
- L’interface d’administration métier

### Hors périmètre :
- L’infrastructure IT interne de l’entreprise
- Les outils bureautiques et collaboratifs
- Le site institutionnel vitrine

---

## 4. Livrables attendus

| Livrable | Description |
|----------|-------------|
| Déclaration de Travail d’Architecture | Ce document |
| Spécification des Conditions Requises | Exigences métier, techniques, de conformité |
| Contrat d’Architecture – Business | Alignement et engagement des parties métier |
| Contrat d’Architecture – Design & Développement | Alignement et gouvernance technique |
| Diagrammes d’architecture | Vues logique, applicative, technique, processus |
| Dépôt GitHub documenté | Centralisation des livrables dans `/doc` |

---

## 5. Processus et framework d’architecture sur mesure

L’architecture sera développée selon une approche **TOGAF ADM**, adaptée aux contraintes d’une startup agile :

- **Phases ADM sélectionnées** : A (Vision), B (Business), C (Systèmes), D (Technologie), E (Opportunités), G (Implémentation)
- Intégration dans une **démarche Agile/Scrum** (sprints d’analyse et d’itération architecture)
- Définition de **vues fonctionnelles, logiques, physiques et technologiques**
- Utilisation de modèles UML, Mermaid et PlantUML pour visualiser les composants
- Collaboration étroite avec les équipes produit et technique

---

## 6. Parties prenantes

| Rôle | Nom ou équipe | Responsabilités |
|------|---------------|------------------|
| Sponsor | CEO Foosus | Valide la vision stratégique |
| Responsable produit | CPO | Définit les priorités métier |
| Équipe tech | Dev Lead, DevOps, Backend | Implémente l’architecture |
| Architecte | Promoteur de l’Architecture | Responsable de la modélisation |
| UX/UI | Designer | Garantit l’expérience utilisateur |
| Utilisateurs pilotes | Groupe bêta | Recueille le feedback terrain |

---

## 7. Planning prévisionnel

| Phase | Période | Résultat attendu |
|-------|---------|------------------|
| 1. Analyse de la situation actuelle | Sem. 1 | Cartographie de l’existant |
| 2. Définition de l’architecture cible | Sem. 2-3 | Vues TOGAF et modèles |
| 3. Validation et revue croisée | Sem. 4 | Contrats d’architecture |
| 4. Dépôt final et soutenance | Sem. 5 | Livraison GitHub + présentation |

---

## 8. Contraintes et hypothèses

- Les ressources techniques sont partagées avec d’autres projets
- L’architecture cible devra **éviter les interruptions de service**
- L’équipe actuelle est partiellement disponible
- Le cadre TOGAF est **allégé et adapté** pour rester pragmatique

---

## 9. Critères de succès

- L’architecture est validée conjointement par les parties métier et techniques
- Les vues produites permettent de guider l’évolution produit sur 12-24 mois
- Les livrables sont réutilisables et extensibles par de futurs architectes
- La structure modulaire favorise la montée en charge et l’intégration future de services externes

---

> Ce document constitue la base de travail de la mission d’architecture pour Foosus
