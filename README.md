# ConstructionWorld
PLP 5A

# AUTHENTIFICATION - Apparaît au lancement du jeu

A - Créer un compte

A la première connexion, le joueur renseigne son pseudonyme, son adresse mail ainsi qu’un mot de passe. Un email de confirmation est envoyé sur sa boite mail.

B - Se connecter
Une fois que le compte a été créé, le joueur peut se connecter en renseignant son adresse mail et mot de passe.

C - Changer de mot de passe
Dans le cas où le joueur oublierait son mot de passe, il a la possibilité de réinitialiser son mot de passe. Il recevra un email lui permettant de choisir un nouveau mot de passe.


# MENU PRINCIPAL - Apparaît après l'authentification

A - Lancer le jeu  partie

Choix entre le mode Facile (2 réponses possibles) / mode dificile (4 réponses possibles).
Affichage du Leaderboard.
Bouton "JOUER".

B - Memento

Affichage de leçons sur des séquences thématiques du domaine de la construction.

C - Règles du jeu

Affiche les règles du jeu

D - Quitter le jeu

Bouton "QUITTER"

E - Tableau des scores

Affiche le top-score de chaque joueur. Bouton "MON SCORE" isole le score personnel du joueur

# ECRAN JEU - Apparaît après le menu, une question, un évènement, un thème

A - Fonctionnement général

Une carte s’affiche sur la partie gauche de l’écran. Elle indique le thème de la séquence actuelle ainsi qu’une question.
Les propositions de réponses sont affichées en bas de l’écran.

Sur la partie droite de l’écran, le joueur peut observer un bâtiment s’élever au fur et à mesure que le joueur répond correctement aux réponses. Cette modélisation 3D permet de représenter une jauge de score.

Un chronomètre est affiché en haut, au centre de l’écran.
Il permet de calculer le score du joueur. Ce calcul se base sur les paramètres suivants :
-	Nombre de checkpoints validés
-	Temps passé à répondre aux questions
-	Nombre de bonnes réponses
-	Nombre de mauvaises réponses

Un bouton permet de quitter la partie en cours de jeu.
B - Transitions mémentos
Les questions s’affichent dans un ordre précis de séquences.
Nous aurons par exemple 5 questions à propos de la séquence “Esquisse” suivies de 5 autres questions sur la séquence “Avant-projet”.

Le passage entre chaque séquence s’effectue par l’affichage d’un mémento (présenté précédemment) qui définit la séquence à venir et permet au joueur de s’instruire.

C - Evènements aléatoires

Des événements apparaîtront de manière aléatoire entre deux questions. 
Ils permettent de représenter les aléas que l’on peut rencontrer dans le domaine du bâtiment. 
Certains sont positifs et offrent 5 points de bonus au joueur. D’autres sont négatifs et se répercutent par un malus de 5 points.

# MENU FIN DE JEU

Une fois la partie terminée, le jeu indique au joueur si la partie est gagnée ou perdue.

La partie est gagnée si le joueur à répondu correctement à 3 réponses pour chacun des 9 checkpoints (représentés par les transitions mémentos).

Cependant, si le joueur fait 3 erreurs dans la même séquence, la partie est perdue.

Le menu de fin affiche le score ainsi que l’avancée du bâtiment.
Si le score est supérieur au record personnel du joueur, il sera alors sauvegardé en base de données.

L’écran de fin offre la possibilité de revenir au menu principal ou bien de quitter le jeu.
