# Projet : Système de Recommandation de Films

## Aperçu du Projet
Ce projet consiste à développer un système intelligent de recommandation de films permettant aux utilisateurs de découvrir de nouveaux films en fonction de leurs préférences.
Que vous soyez fan de science-fiction, de comédies ou de drames, ce système vous propose une liste personnalisée de films similaires à ceux que vous aimez déjà.

### Problème Commercial
#### *Contexte :* 
Avec l'explosion de l'offre de contenus cinématographiques, les utilisateurs sont souvent submergés par le choix.
Il devient difficile de :

- Trouver rapidement un film qui correspond à leurs goûts.

- Découvrir des films moins connus mais susceptibles de les intéresser.

- Optimiser leur temps de recherche.

#### *Objectif :* 
Créer un outil simple et efficace pour :

- Améliorer l’expérience utilisateur en proposant des recommandations pertinentes.

- Fidéliser les utilisateurs en leur offrant un service personnalisé.

- Valoriser le catalogue de films en mettant en avant des contenus adaptés.

#### *Pour les parties prenantes : :*

* Équipe produit de la plateforme de streaming

* Utilisateurs finaux cherchant des recommandations personnalisées

* Équipe data science pour maintenance et amélioration

 ### Jeu de Données 
#### *Le dataset MovieLens contient :* 
movies.csv (déjà fourni) : informations sur les films (titre, genres)

À ajouter :

ratings.csv : évaluations des utilisateurs (userId, movieId, rating, timestamp)

tags.csv : tags attribués par les utilisateurs (userId, movieId, tag, timestamp)

links.csv : liens vers IMDb et TMDB (movieId, imdbId, tmdbId)

### Objectifs Techniques

#### Données utilisées :
- Descriptions des films (titres, genres, années).

- Notes et évaluations des utilisateurs.

- Tags et mots-clés associés aux films.

### Fonctionnalités principales :
- Recherche de films par titre ou mot-clé.

- Recommandations basées sur le contenu : similarité des genres, tags, etc.

- Calcul de popularité : prise en compte des notes et du nombre de votes.

- Interface interactive pour tester le système en temps réel.

### Conclusion
Ce projet vise à concevoir et développer un système de recommandation de films basé sur le contenu, utilisant des techniques de traitement de données et d'apprentissage automatique. Les données proviennent de plusieurs fichiers (films, évaluations, tags, liens) qui sont fusionnés et enrichis pour créer un jeu de données complet.

#### Les principales étapes incluent :

- Le prétraitement des données (nettoyage des titres, extraction des genres)

- La création de caractéristiques avancées (combinaison des genres et tags, score de popularité)

- La vectorisation des caractéristiques textuelles via TF-IDF

- Le calcul de similarités cosinus entre les films

- L'implémentation de fonctions de recherche et de recommandation

#### Le système permet aux utilisateurs de :

- Rechercher des films par titre

- Obtenir des recommandations basées sur la similarité de contenu

- Consulter les métriques associées (notes, similarité)

Une interface interactive simple est proposée pour tester le système. Le projet démontre l'application pratique des techniques de science des données pour créer un outil de recommandation personnalisé, avec des visualisations pour analyser la distribution des films par genres et popularité.
             
