# GENEALOGIE BOUT EN BOUT: GUIDE

## Objectif de ce document 

Ce document a pour bojectif d'expliquer ce qui est atendu dans la réalisation d'une généalogie de bout-en-bout. 
Il a pour objectif de compléter le template de généalogie de bout)e,n-bout

## Guide d'utilisation du template de généalogie

### Information sur le modèle
   
Toutes les informations nécessaires à l'identification du modèle. 

- Personne / Organisation en charge du développement du modèle     

    - L'objectif est d'identifier les personnes physiques et morales qui sont intervenues lors de la création du modèle 
    - Lorsque la création du modèle repose sur plusieurs parties prenantes, l'ensemble de la chaine de responsabilité doit être décrite 

- Personne / Organisation en charge de la validation du modèle     

    - Quelles sont les personnes moorales / physiques qui ont validé le modèle ? 
    - Mise en place d'un audit / d'une certification ? 

- Date de création / modification du modèle / Version

    - L'objectif est de fournir l'historique du modèle, les différentes versions et écolutions de celui-ci

- Type de modèle
    
    - Préciser le type aide à comprendre les hypothèses et méthodes appliquées à sa construction (classification de Bayes? réseaux de neurones ? ..)
    - Quel modèle initial a été utilisé ? 

- Type d'apprentissage

    Préciser le typde d'apprentissage réalisé (transfer learning, distributed learning, etc...)

- Resources pour plus d'information 
    
    - Toutes les ressources / liens qui peuvent aider à mieux comprendre le modèle et son fonctionnement (papier de recherche, présentation, etc...)

- License 

    - Sous quel license s'applique le modèle (open source, license privée, etc...) ?

- Information de contact et envoyer des feedbacks 
    
    - E-mail ou autre d'une personne physique pour contacter si besoin d'avoir un échange à propos du modèle


### Motivations et Objectifs du modèle 

Toutes les informations nécessaires pour comprendre rapidement le contexte d'utilisation ainsi que le cadre d'analyse statistique du modèle.

- Objectif principal du modèle / cas d'usage premier

    - Description précise du cas d'usage et de l'objectif premier du modèle : quelle est son application  ? A quoi doit il servir ? Qu-estce qu'il prédit et dans quel but ? 

- Destinatères principaux
    
    - Quels sont les utilisateurs principaux du modèle ? 
    - Quels sont les "clients finaux" du modèle ? 
    - Autres parties prenantes impactées par le modèle ? 

- Impacts "Out-of-scope" 

    - Autres potentiels utilisations du modèle dans d'autres contextes ? 
    - Possibilité d'utiliser certaines parties dans d'autres aplications (modèles, datasets, algorithme)

-  Limites d'utilisation du modèle 

    - Quelles sont les limites d'utilisation du modèle ? 
    - Quelles sont les domaines de non application du modèle ? 

### Explicabilité 

L'explicabilité permet de comprendre la performance du modèle à travers une variété de features / facteurs

- Explicabilité 

    - Quels sont les features essentiels qui explique une variation de performances ?
    - Comment ont-ils été identifiés ? 

- Fairness 

    - Quelles mesures de fairness ont été implémentées ? 
    - Comment les potentiels problèmes de biais ont été adressés ? 


### Metrics de performance 

En fonction de la structure et de l'objectif du modèle, des métriques spécifiques ont été utilisées. Elles doivent être indiquées ci-dessous

- Mesure de performance

    - Quelles mesures de performance ont été utilisées ? Pourquoi avoir choisi ces mesures ? 

- Performance dans la recherche 

    - Dans la rrecherche, quelles sont les performances généralement obte nues pour ce type de problème. 

- Seuils pertinents 

    - Quels seuils de décisions ont été définis ? Quelle plages d'indécisions ont été définies ? Comment ?

- Robustesse 

    - Qeulles metrics de robustesses ont été mises en place ? 
    - Comment les performances sont mesurées dans le temps ? 

### Jeux de données 

Présentation des jeux de données utilisés pour l'apprentissage du modèle et la validation de la performance. 

- Datsets

    - Quels sont les datasets qui ont été choisis ? 
    - Comment ont été collectées les données 
    - Utilisation de données synthètiques ? 
    - Comment sont traités les données "manquantes" ? 

- Contrôle qualité 

    - Quels contrôles sur la qualité des données ont été mis en place ? 

- Preprocessing 

    - Quel(s) algorithme(s) de préprocessing ont été utiliséss pour préparer les données 

- Séparation des jeux de données 

    - Quel algorithme a été utilisé pour séparer les données en train / test / validation ? 
    - Comment est assuré la représentativité des différents jeux de données ? 

- Sécurité et confidentialité des jeux de données 

    - Le jeu de données contient-il des informations personnelles et confidentielles ? 
    - Comment est préservée la confidentialité de ses données ? (encryptage, etc...)

### Sécurité du modèle et des algorithmes

Présentation des différentes techniques pour protéger le modèle et les algorithmes. 

- Privacy enhancing technologies 

    - Quelles techniques d'amélioration de la confidentialité ont été mises en places ? 

### Autres considérations 

Autres informations pertientes reliée au modèle. 
  
- Considerations ethique

    - Est-ce que les considérations éthique ont été identifiés /  étudiées, ainsi les défis qui en découlent ?

- Recommandations et Mises en garde

    - Quelle limites d'utilisations au modèle ont été mises en places ? 

- Impacts sociétaux estimés du modèle 

    - Est-ce que les impacts sociétaux du modèle ont été étudiés ? 
    - Quelles mesures ont été mises en place ? 

- Impacts sociétaux estimés du modèle 

    - Est-ce que les impacts environnementaux du modèle (de son apprentissage a sa mise en production) ont été étudiés ? 
    - Quelles mesures ont été mises en place ? 
