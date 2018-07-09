# AndroidFlickster
# Projet 1 - * Flickster*

** Flickster ** montre les derniers films actuellement en salles. L'application utilise l'API Movie Database pour afficher des images et des informations de base sur ces films à l'utilisateur.

Temps passé:  72 heures heures passées au total

## Histoires d'utilisateurs

La fonctionnalité requise suivante est terminée:

 [] L'utilisateur peut faire défiler les films actuels à partir de l'API Movie Database
[] La mise en page est optimisée avec le motif [ViewHolder] (http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView#improving-performance-with-the- viewholder-pattern).
 [] Pour chaque film affiché, l'utilisateur peut voir les détails suivants:
   [] Titre, Image de l'affiche, Vue d'ensemble (Mode Portrait)
   [] Titre, Image de fond, Vue d'ensemble (Mode paysage)

Les fonctionnalités optionnelles suivantes sont implémentées:

[] Afficher une belle valeur par défaut [graphique d'espace réservé] (http://guides.codepath.com/android/Affichage-Images-avec-la-Picasso-Library#configuring-picasso) pour chaque image lors du chargement.

Les fonctionnalités bonus suivantes sont implémentées:

 [] Permet à l'utilisateur d'afficher les détails du film, y compris les classements et la popularité, dans une activité ou un fragment de dialogue distinct.
 [] Lors de la visualisation d'un film populaire (c.-à-d. Un film voté pour plus de 5 étoiles), la vidéo devrait montrer l'image de fond complète comme mise en page. Utilise [ListViews hétérogènes] (http://guides.codepath.com/android/Implementing-a-Heterogenous-ListView) ou [Heterogenous RecyclerView] (http://guides.codepath.com/android/Heterogenous-Layouts-inside- RecyclerView) pour afficher différentes dispositions.
 [] Autoriser la lecture des bandes-annonces en plein écran à l'aide de YouTubePlayerView.
    [] Superposition d'une icône de lecture pour les vidéos pouvant être lues.
     [] Les films les plus populaires doivent démarrer une activité distincte qui lit la vidéo immédiatement.
     [] Les vidéos moins populaires comptent sur la page de détails pour afficher les évaluations et un aperçu de YouTube.
 [] Appliquez la populaire [bibliothèque d'annotations Butterknife] (http://guides.codepath.com/android/Reducing-View-Boilerplate-with-Butterknife) pour réduire le code standard.
 [] Appliquer des coins arrondis pour les images d'arrière-plan ou d'affiche en utilisant [Transformations Picasso] (https://guides.codepath.com/android/Affichage-Images-avec-la-Picasso-Library#other-transformations)
 [] Remplacement du client réseau android-async-http avec les bibliothèques de réseautage populaires [OkHttp] (http://guides.codepath.com/android/Using-OkHttp).

Les fonctionnalités ** supplémentaires ** suivantes sont implémentées:

[] Liste toute autre chose que vous pouvez faire pour améliorer la fonctionnalité de l'application!

## Procédure pas à pas vidéo

Voici une présentation des user stories implémentées:

<img src = 'http: //i.imgur.com/link/to/your/gif/file.gif' title = 'Vidéo Procédure pas à pas' width = '' alt = 'Vidéo Procédure pas à pas' />

GIF créé avec [LiceCap] (http://www.cockos.com/licecap/).

## Remarques

j'avais des difficultes a utilises Picasso dans le projet

## Bibliothèques open-source utilisées

- [HTTP asynchrone Android] (https://github.com/loopj/android-async-http) - Requêtes HTTP asynchrones simples avec analyse JSON
- [Picasso] (http://square.github.io/picasso/) - Bibliothèque de chargement et de mise en cache d'images pour Android

## Licence

    Droit d'auteur [yyyy] [Desilias Dimitry]

    Sous licence Apache, Version 2.0 (la "Licence");
    Vous ne pouvez pas utiliser ce fichier sauf en conformité avec la licence.
    Vous pouvez obtenir une copie de la licence à

        http://www.apache.org/licenses/LICENSE-2.0

    Sauf si requis par la loi applicable ou accepté par écrit, logiciel
    distribué sous licence est distribué "TEL QUEL",
    SANS GARANTIE OU CONDITION D'AUCUNE SORTE, expresse ou implicite.
    Voir la licence pour la langue spécifique régissant les autorisations et
    limitations en vertu de la licence.
