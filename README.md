Projet 3 du parcours Développeur web d'OpenClassrooms : Dynamiser un site web avec des animations CSS

I/ Contexte

Ohmyfood! est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants car les menues sont préparés à l'avance.

II/ Objectifs

Phase 1: Développer un site proposant le menu de 4 grands restaurants parisiens.
Phase 2: Permettre la réservation en ligne et la composition de menus.

III/ Technologies

Autorisées : HTML/ CSS
Recommandée : Sass
Interdites: Javascript/ Framework/ Inline CSS

IV/ Livrables

1) Contenu des pages

Page d'accueil (x1)
Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
Une courte présentation de l'entreprise.
Une section contenant les 4 menus sous forme de cartes. Au clic sur la carte, l'utilisateur est redirigé vers la page du menu.

2) Page de menu (x4)
4 pages contenant chacune le menu d'un restaurant.

Footer
Le footer est identique sur toutes les pages.
Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

Header
Le header est présent sur toutes les pages.
Sur la page d'accueil, il contient le logo du site.
Sur les pages de menu, il contient en plus un bouton de retour vers la page d'accueil.


2) Effets graphiques et animations

Boutons
Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, unbouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol au lieu du clic.

Page d’accueil
Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,toute proposition est donc la bienvenue tant qu’elle est cohérente avec la chartegraphique du site.

Pages de menu
À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser dela droite vers la gauche. Pour cette première version, l’effet peut apparaître au survolau lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni

V/ Identité graphique

Polices :
Logo et titres : Shrikhand
Texte : Roboto

Couleurs :
Primaire: #9356DC
Secondaire: #FF79DA
Tertiaire: #99E2D0

VI/ Compatibilité
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.

L’ensemble du site devra être responsive sur mobile, tablette et desktop.
Les pages devront passer la validation W3C en HTML et CSS sans erreurs.
Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

URL du site: https://pricilliaedouedou.github.io/PricilliaEDOUEDOU_3_04082021/