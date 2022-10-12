# ConstructionWorld
PLP 5A

# ############################################ #
# DEFINITION DES ECRANS - cf Maquette Balsamiq #
# ############################################ #

# ECRAN MENU - Apparaît au lancement du jeu, après le menu de fin
Choix entre le mode Facile (2 réponses possibles) / mode dificile (4 réponses possibles).
Affichage du Leaderboard.
Bouton "JOUER".

# ECRAN QUESTION - Apparaît après le menu, une question, un évènement, un thème
Animation d'une carte qui s'affiche. Contient une question.
Affichage des réponses. Bouton se colore en vert/rouge en fonction de la validité de la question.
Animation d'un bâtiment qui se construit selon l'avancée dans le jeu.
Affichage du temps.

# ECRAN EVENEMENT - Apparition aléatoire après une question
Animation d'une carte qui s'affiche. Contient un évènement.
Animation d'un bâtiment qui se construit selon l'avancée dans le jeu.
Animation appliquée sur tout l'écran / sur le model de bâtiment 3D.
Affichage du temps.

# ECRAN THEME - Apparaît à chaque nouveau thème, entre deux questions
Image en fond d'écran.
Texte de description du thème.
Bouton "SKIP".

# ECRAN FIN DE JEU - Apparaît après la dernière carte jouée
Affichage du score.
Bouton "Enregistrer le score". Lance un pop-up pur renseigner le pseudo du joueur.
Bouton "Reveir au menu".
Affichage du bâtiment 3D.


# ####################### #
# DEFINITION DES ELEMENTS #
# ####################### #

# DEROULEMENT DU JEU
Chaque carte représente une situation, en fonction de la réponse, la jauge évolue.
La jauge est représentée par un chantier/une maison qui se construit si la réponse est bonne, stagne si la réponse est mauvaise.
Possibilité de choisir entre le mode Facile (2 réponses possibles) / mode dificile (4 réponses possibles).
Système d’étapes d'un chantier dans lesquelles les cartes questions seront jouées aléatoirement afin d'éviter la redondance. 
- Programmation et montage
- Conception
- Chantier (subdivisé ?)
- Exploitation et fin de vie
Des cartes évenement et thème peuvent apparaître.
Calcul du temps de jeu. Traduction secondes en journées.
Partie gagnée si X questions correctement répondues par thème. Partie perdu sinon.

# CARTES
Design graphique pour toutes les cartes d'un thème. Idée : exploiter des IA.
Chaque carte contient une question / un évènement.
Stockage : à définir ??

# MODELISATION DU BATIMENT EN 3D
A définir ??

# MODELISATION DES EVENEMENTS
A définir en fonction des évènements ??
Modifie le temps affiché sur le chrono.

# SCORE
Leader-bord sur l'écran principal. Contient le psudo et le score associé.
Fonction de tri Leader-board global / personnel ??
Calcul en fonction de la difficulté + des questions correctement répondues + du temps de réponse

# ################ #
# CHOIX TECHNIQUES #
# ################ #

# PLATEFORMES
Ordinateurs Windows (peut-être MacOS et Linux)

# HOST
Gestion de comptes et score : Dans unreal ungine via Gamespark.
Leaderboard : Dans unreal ungine ?? Temps réel ou gardé en mémoire dans une BDD