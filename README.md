# P3_Ohmyfood

Identite: Ohmyfood! est une entreprise de commande de repas en ligne.

Concept: permetre aux utilisateurs de composer leur propre menu et de réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance.

Proposition : Déjà présent à New-York > développement à Paris.

Positionnement : Cuisine gastronomique, services haut de gamme

Cible : Classes moyennes et supérieures, connectées et pressées.


Contraintes graphiques et fonctionnelles :

* Polices : Shrikhand (Logo et titres) / Roboto
* Couleurs : Primaire #9356DC / Secondaire #FF79DA / Tertiaire #99E2D0
* Technologies
    ● Développement en CSS, sans JavaScript.
    ● Aucun framework, mais utilisation de SASS serait un plus.
    ● Aucun attribut style dans une balise HTML.
    ● Code doit être versionné sur GitHub et site doit être accessible sur Github Pages
* Approche mobile first, site responsive sur mobile, tablette et desktop.
* Validation W3C en HTML et CSS sans erreur.
* Site compatible avec les dernières versions desktop de Chrome et Firefox


Livrables attendus

🟣 Contenu des pages

Page d’accueil (x1)
● Affichage localisation restaurants.
● Présentation de l’entreprise.
● Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

Pages de menu (x4)
● 4 pages contenant chacune le menu d’un restaurant.

Footer
● Le footer est identique sur toutes les pages.
● Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

Header
● Le header est présent sur toutes les pages.
● Sur la page d’accueil, il contient le logo du site.
● Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil


🟣 Effets graphiques et animations
Les effets accessibles au clic ou au survol devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

Boutons
● Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
● Bouton "J’aime" en forme de cœur sous chaque restaurant. Au survol (ultérieurement au clic), il devra se remplir progressivement. 

Page d’accueil
● Donner un aperçu d'un “loading spinner” : il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran. Proposition libre tant qu’elle est cohérente avec la charte graphique du site.

Pages de menu
● À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. 
● Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, effet au survol.
Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. 