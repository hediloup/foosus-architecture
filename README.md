
## Projet 5 – Concevez une nouvelle architecture afin de soutenir le développement de **Foosus**
Bienvenue dans ce dépôt GitHub dédié à la modélisation de l’architecture d’entreprise de **Foosus**, une startup de l’alimentation durable.

Ce projet s’inscrit dans le cadre du Projet 5 et repose sur le cadre méthodologique **TOGAF**. Il propose une architecture évolutive, modulaire et alignée sur les besoins stratégiques de l’organisation.

## Objectifs
- Définir une vision claire de l’architecture cible pour Foosus
- Cadrer les exigences techniques et fonctionnelles
- Établir des accords formels avec les parties prenantes (Business, Design, Développement)
- Livrer un dépôt structuré et navigable pour les revues

## Structure du dépôt
```bash
/doc
├── 01-Declaration-Travail-Architecture.md
├── 02-Conditions-Requises-Architecture.md
├── 03-Contrat-Architecture-Business.md
├── 04-Contrat-Architecture-Technique.md
├── assets/          # Images, schémas, diagrammes
├── diagrams/        # Fichiers PlantUML ou draw.io
```

## Livrables TOGAF
|
├── Déclaration de Travail d’Architecture : Vision, état cible et processus d’architecture 
├── Spécification des Conditions Requises pour l’Architecture : Exigences d’implémentation et de conformité 
├── Contrat d’Architecture – Utilisateurs Business : Engagements mutuels avec les parties métier 
├── Contrat d’Architecture – Fonctions Design & Développement : Engagements avec les équipes techniques

## Diagrammes et visualisations
Les diagrammes sont disponibles dans le dossier `/doc/diagrams`.
```mermaid
flowchart TD
  Vision("Vision d'Architecture")
  EtatCible("État Cible de l'Architecture")
  Exigences("Conditions Requises")
  Business("Contrat Business")
  Technique("Contrat Design & Développement")

  Vision --> EtatCible --> Exigences --> Business
  Exigences --> Technique


## Comment utiliser ce dépôt
1. Parcours les livrables dans l’ordre : de la vision jusqu’aux engagements techniques.
2. Consulte les schémas pour visualiser la structure cible.
3. Utilise ce dépôt comme support lors de la présentation orale.

## Licence
Ce projet est sous licence. Voir le fichier [LICENSE](./LICENSE) pour plus de détails.

## Auteur
**Hedi Dhib**  

