# Distillation de modèles 

Membres : ...

## Objectifs 

Etudier les techniques de distillation de modèles et écrire un guide technique, article de blog, etc... autour de ce thème. 

## Organisation

Trello - [To do list](https://trello.com/b/PFb5SOOA/data-for-good-to-do-list)

## Ressources

- (Web article) La *distillation* d'un modèle, en plus de la compression qu'elle apporte, peut être utilisée comme une mesure de protection du modèle et des données d'entraînement utilisées, voir par exemple *[Knowledge Distillation : Simplified](https://towardsdatascience.com/knowledge-distillation-simplified-dd4973dbc764)*, Towards Data Science, 2019
- (Tool) [distiller](https://nervanasystems.github.io/distiller/index.html)
- [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)
- [Exploring KD of Deep NN for hardware efficient solutions](http://cs230.stanford.edu/files_winter_2018/projects/6940224.pdf)
- [Research Guide: Model Distillation Techniques for Deep Learning (Medium)](https://heartbeat.fritz.ai/research-guide-model-distillation-techniques-for-deep-learning-4a100801c0eb)
arXiv.orgarXiv.org

## Premiers travaux

-  L'angle d'approche est souvent la compression de modèles après l'utilisation de transfer learning (principalement en NLP & computer vision) pour les rendre moins gourmands en ressources. On va vouloir répliquer la performance sur une application spécifique sans garder les millions de paramètres que peut avoir un algo pré-entrainé (BERT, etc..)
- Les modèles pris pour exemple sont des réseaux de neurones, souvent profonds.