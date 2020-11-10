# GENEALOGIE BOUT EN BOUT: MODELE #

## Objectif de ce document 

Un modèle prédictif est un objet informatique complexe qui peut évoluer au fil des apprentissages. Tracer les étapes de son élaboration et de son évolution permet d’en constituer une forme de généalogie, pré-requis pour reproduire ou auditer un modèle. Par ailleurs utiliser des systèmes automatiques basés sur des modèles dont les règles ont été “apprises” (et non définies et formalisées) interroge le fonctionnement des organisations. Il apparaît indispensable de garantir une chaîne de responsabilité claire, de personnes physiques ou morales, pour chaque modèle.

Ce concept de “généalogie de bout-en-bout” d’un modèle prédictif appris peut se décliner sous la forme par exemple d’un document de référence reprenant tous les choix importants ainsi que tout l’historique d’élaboration du modèle (données utilisées, pré-traitements réalisés, type d’apprentissage et architecture du modèle, seuils de décision, métriques de tests...), etc.), et de processus internes organisant cette activité. En particulier, il est intéressant d’y faire figurer les choix de compromis (trade-offs) qui ont été faits et pourquoi (e.g. trade-offs précision-spécificité, performance-privacy, performance-coût computationnel, etc.).

Pour accompagner votre projet, ce document est un template pour vous aider à collecter toutes les informations afin de tracer la généalogie de bout-en-bout de votre modèle. 
C'est un outil efficace pour améliorer la compréhension de ce modèle, de standardiser la prise de décision et d'assurer son intégrité. 

## Template


### Information sur le modèle

    - Personne/Organisation en charge du développement du modèle 
    - Date 
    - Version
    - Type 
    - Ressouces pour plus d'information
    - License
    - Information de contact 

### Motivations et Objectifs du modèle 

    - Principales/premières
    - Destinatères principaux
    - Impacts hors champ 

### Facteurs (démographie, conditions environnementales, attributs techniques ....)
    
    - Pertinents 
    - Evaluation 

### Metrics : 

    - Mesure de performance utilisée 
    - Seuils pertinents 
    - Approches de variation

### Evaluation de la donnée (analyse quantitative): 
    - Datasets utilisés 
    - Preprocessing 

(Donnée d'entrainement si applicable)

### Autres considétations 

    - Considerations ethique
    - Mises en garde
    - Recommandations
    - Impacts écologiques estimés du modèle 




Source: 
    - Model Card for Model Reporting, 2019: https://arxiv.org/pdf/1810.03993.pdf 

