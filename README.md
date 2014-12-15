# Rendu NIHM de damien druel

### Téléchargement 

	https://github.com/nio59/Rendu_France/raw/master/France_Druel.zip

### Avancement du TP

	Le tp à été fait jusqu'a l'etape 6 du TP3, c'est à dire en entier sauf les questions bonus.

### Comment lancer l'application ?

	Double clique sur France.pde puis clique sur la bouton play.
	Les touches disponibles sont la flèche gauche pour baisser le seuil et la flèche droite pour l'augmenter.

### Choix visuels


	Les villes sont représentées par une ellipse.
		- La taille de l'ellipse est proportionnelle à la densité de population
		- La couleur indique l'altitude
			- Vert (altitude < 100)
			- Jaune (100 < altitude < 200)
			- Orange (200 < altitude < 500)
			- Rouge (500 < altitude < 1000)
			- Noir (altitude > 1000)
			
		- Lorsqu'on passe la souris sur une ville, la couleur de l'ellipse change
			
			- Vert (population < 10 000)
			- Jaune (10 000 < population < 100 000)
			- Orange (100 000 < population < 250 000)
			- Rouge (250 000 < population < 500 000)
			- Noir (population > 500 000)
	

		- Enfin on affiche le nom de la ville et le nombre d'habitant dans une rectangle
		
#### Sources

	http://fr.wikipedia.org/wiki/Processing
	https://processing.org/examples/
	https://processing.org/tutorials/
	http://docs.oracle.com/javase/6/docs/api/constant-values.html (code des touches)
	https://www.processing.org/reference/keyCode.html (pour la fonction KeyPressed)
	

