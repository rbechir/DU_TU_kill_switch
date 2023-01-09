# DU_TU_kill_switch
Script permettant de démarrer/arrêter plusieurs TUs à l'aide d'un seul bouton
## Instructions d'installation
### Matériel requis :
- Programming Board : 1 PB (master) peut gérer jusqu'à 8 TUs, chaque PB supplémentaire peut gérer 9 TUs de plus
- 1 Relay
- 1 Manual Button : XS ou S, peu importe
- 1 Databank
- 1 Light : n'importe quel type de lumière fait l'affaire
### Ordre de connexion
Coller le contenu du fichier code.json dans les PBs.  
Il est indispensable de suivre l'ordre de connexion pour que le script fonctionne bien.
- Connecter tous les PBs au Databank
- Connecter le PB master à la Light
- Connecter les PBs aux TUs (noter l'ordre de connexion)
- Connecter le Button au Relay
- Connecter le Relay aux PBs
### Initialisation
Accéder aux variables LUA sur les différents PBs :
- S'assurer que seul le PB master a la case "master" cochée
- Entrer les maintain des différents TUs connectés (en suivant l'ordre de connexion noté précédemment)
## Utilisation
Appuyer sur le bouton pour arrêter/relancer tous les TUs d'un coup.  
Attention à bien rester appuyé sur le bouton jusqu'à ce que la lumière change de couleur, ou jusqu'à ce que le widget du PB ait disparu.
