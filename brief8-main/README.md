# brief8 - Les modèles dans tous leurs états

Le but de ce brief est de créer des tutoriels d'utilisation de modèles de machine learning pour des étudiants qui débutent avec scikit-learn. Mais aussi concevoir des exercices de bases pour que ces étudiants puissent se faire la main sur la librairie. 

Les briefs seront codés avec le langage Python avec l'outil de travail Jupyter Notebook. Plusieurs librairies vont être utilisées : pandas, numpy, matplotlib, sklearn. Les modules de sklearn seront la plupart du temps exploités pour l'usage du machine learning tel que model_selection (train_test_split), metrics (mean_squared_error, r2_score), datasets, etc...
Voici les commandes pour les installer:
```
pip install pandas
pip install numpy
pip install matplotlib
pip install -U scikit-learn
```

## Résumé des 4 tutoriels

 - la régression linéaire sera utilisé avec le dataset California Housing pour estimer le prix d'un bien à partir des paramètres d'entrée donnés dans le dataset.
 - la méthode k-means sera utilisée avec le dataset Iris pour trouver des groupes de fleurs, sans information préalable sur le type de fleur disponible dans le dataset (de manière aveugle).
 - le modèle SVM sera utilisé avec le dataset hand-written digits pour reconnaître les chiffres de 1 à 10 à partir des images fournies dans le dataset. Pour cette partie, je me suis fortement inspiré du tutotiel de Valentin. J'ai juste changé le type de modélisation.
 - le dernier est juste un tutoriel sur divers fonctions train_test_split, cross_validation et validation_curve de sklearn pour mieux les comprendre. J'ai utilisé le dataset des fleurs d'iris pour les exemples.

## Planning

[Afficher - PDF version](pdf/Planning.pdf)
