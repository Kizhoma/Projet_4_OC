# Ohmyfood
Quatrième projet du parcours "Intégrateur web" chez OpenClassroom. L'objectif d'intégrer puis de dynamiser une page web avec des animations CSS en utilisant le préprocesseur Sass

Vous pouvez retrouver [le brief complet ici](https://course.oc-static.com/projects/Développeur+Web/IW_P4+Animations+CSS+Ohmyfood/Brief+créatif+site+Ohmyfood.pdf)


![image](https://user-images.githubusercontent.com/94898151/207743875-ad985360-7ae5-44d1-bd2d-6f14015fa138.png)


## Objectifs

- Développer un site proposant le menu de 4 grands restaurants parisiens.
- Permettre la réservation en ligne et la composition de menus.

## Livrables

- Fonctionnalités:

    - Page d'accueil: 

        * Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
        * Une courte présentation de l’entreprise.
        * Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.
   
    - Pages de menu:

        * 4 pages contenant chacune le menu d’un restaurant.

    - Footer:

        * Le footer est identique sur toutes les pages.
        * Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

    - Header:

        * Le header est présent sur toutes les pages.
        * Sur la page d’accueil, il contient le logo du site.
        * Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

## Animation    
   
- Effet graphique et animations:

     - Boutons:

        * Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
        * À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.


     - Page d’accueil:

        * Quand l’application aura plus de menus, un “loader” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

     - Pages de menu:

        * À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront apparaître soit un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
        * Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

- Contraintes techniques:

    - Le développement doit se faire en CSS, sans JavaScript.
    - Le code CSS doit être disponible dans un ou plusieurs fichiers dédiés.
    - Le développement doit se faire en CSS, sans JavaScript.
    - Le site devra être réalisé en adoptant le Mobile First, c’est-à-dire qu’il faudra d’abordréaliser l'intégration de la maquette mobile, puis tablette, et enfin l'intégration du responsive vers le desktop.
    - Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
    - Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
    - Les couleurs de la charte sont, en couleur primaire le #9356DC, en couleur secondaire le #FF79DA, et en couleur tertiaire le #99E2D0.
    - La police du site est, Logo et titres Shrikhand, et Texte: Roboto.
    - Tout le code doit être versionné sur GitHub avec des commits réguliers pour suivre l’avancement et publier le site en ligne plus facilement.
    - Le site devra être accessible sur GitHub Pages une fois terminé.

- Contraintes d'exercices:

    - L’ensemble du site devra être responsive sur mobile, tablette et desktop.
    - Les pages devront passer la validation W3C en HTML et CSS sans erreur.
    - Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

## Technologies

- HTML
- CSS
- SASS
- Font Awesome ( importation d'icones )
- Google Font: Logo et titres Shrikhand, Texte: Roboto ( importation des links )

## Licenses

- Font Awesome ( utilisation d'icones gratuits )
- GitHub ( stockage gratuit des fichiers et déployement gratuit sur GitHub pages )
- Google Font ( utilisation de police d'écriture gratuite )
- SASS ( utilisation de préprocesseur gratuite )