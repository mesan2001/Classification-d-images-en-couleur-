
Projet de Classification d'Images - CIFAR-10-like
I- Aperçu du Projet

Ce projet consiste en un mini-challenge de classification d'images inspiré du dataset CIFAR-10, où l'objectif est de prédire la classe de 10 000 images de test à partir d'un ensemble d'entraînement de 20 000 images étiquetées. Les images, en couleur et de taille 32x32 pixels, sont réparties en 10 classes (avions, voitures, chats, chiens, etc.).

Le projet a été réalisé dans le cadre d'un cours de Machine Learning, avec pour but de comparer différentes approches de classification et d'optimiser les performances des modèles.
II- Objectifs

✔ Pré-traiter et visualiser les données (TSNE, affichage par classe).
✔ Implémenter et comparer plusieurs algorithmes de classification :

    k-NN (k plus proches voisins)

    Régression logistique multivariée

    Réseaux de neurones (MLP et CNN)
    ✔ Évaluer les performances via la plateforme Codalab et analyser les résultats.

III- Méthodologie
1. Exploration des Données

    Visualisation d'images : Affichage d'échantillons par classe.

    Réduction de dimension (TSNE) pour observer la séparabilité des classes.

2. Modèles Testés
Modèle	Précision	Avantages/Inconvénients
k-NN	XX%	Simple, mais lent en prédiction
Régression Logistique	XX%	Rapide, mais limite sur données complexes
CNN	XX%	Meilleure performance, capture des motifs spatiaux

3. Optimisation

    k-NN : Recherche du meilleur *k* par validation croisée.

    CNN : Ajout de couches de convolution, dropout et early stopping.

4. Résultats

    Meilleur modèle : CNN avec XX% de précision sur le leaderboard Codalab.

    Analyse :

        Les méthodes traditionnelles (k-NN, régression logistique) sont moins performantes sur des données aussi complexes.

        Le CNN surpasse les autres grâce à sa capacité à extraire des features hiérarchiques.


   
