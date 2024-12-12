Date : 06/12/2021

Auteurs : 

	  Programmeurs :		Graphistes :
	  Antoine Richard		Maëva Henschen
	  Anthony Bach			Lana Gratreaud
	  Luc D'Eurveilher
	  Yohann Morits

Description :

	  Il s'agit d'un jeu de type Rogue-Like où l'on incarne une héroïne équipée d'une amulette magique dont l'objectif est de libérer un chateau de l'emprise des monstres de la forêt.

Contrôles : 

		Général :
	    - Entrée : passer l'intro (les logos) / confirmer la sélection.
	    - Echap : quitter le jeu / revenir sur l'écran précédent (dans les menus).
	    - Tab : afficher l'inventaire (en jeu) / permuter entre la configuration QWERTY et AZERTY (dans le menu 'keys')

		Jeu :
	    - Clic gauche : tirer en continu, bouger le curseur permet de viser.
	    - P : mettre le jeu en pause.
	    - Touches configurables : se déplacer (par défaut : "ZQSD").

		Inventaire :
	    - A (ou Q en QWERTY) : utiliser l'item de soin (dans l'inventaire)
	    - E : utiliser l'item de vitesse d'attaque (dans l'inventaire)
	    - R : utiliser l'item d'augmentation des dégâts (dans l'inventaire)

		Minimap:
	    - M (ou ; en QWERTY) : afficher et cacher la mini-map (en jeu).
	    - L : déplacer la mini map (en jeu).

Fonctionnalités :

	- Le joueur peut naviguer dans les menus afin de lancer une partie, configurer ses contrôles, afficher les crédits et quitter le jeu.
	- Le joueur peut tirer des projectiles et tuer les ennemis (les projectiles infligent 1pt de dégat au début du jeu).
	- Découvrir une nouvelle salle donne 1 point d'expérience. Celui-ci servira à acheter un item d'amélioration dans l'inventaire.
	- Le Wendigo (5 PV) est un ennemi de type mêlée qui fonce sur le joueur pour l'attaquer. Ses attaques infligent -20 PV au joueur.
	- Le Feu follet (2 PV) est un ennemi de type distance qui suit très lentement le joueur et tire un projectile sur celui-ci. Ce projectile inflige -5 PV au joueur.
	- La Mini-map affiche la position actuelle du joueur, les salles qu'il a exploré et celles qui sont encore à découvrir.
	- Le joueur peut déplacer la mini-map où il le souhaite à l'aide de la touche "L".
	- L' HUD comporte les PV, la vitesse d'attaque et la puissance du joueur ainsi que le nombre de salles qu'il a découvert et le nombre de points d'expérience qu'il a récolté.
	- La caméra suit le joueur dans les couloirs.
	- Le joueur gagne après avoir survécu à toutes les salles du château.

Bugs connus :

	Aucun bug connu. (vraiment)


Crédits Musicaux : 
"Steffen Daum - Awakening" is under a creative commons music license (CC BY 3.0)
Musique promue par BreakingCopyright: https://bit.ly/b-awakening

"Darren Curtis - It's In The Fog" is under a Creative Commons license (CC BY 3.0).
Musique promue par BreakingCopyright: https://bit.ly/b-in-the-fog

