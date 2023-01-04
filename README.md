# Projet NF19 - A22

Réalisé par Luna Schenk et Lucas Sauron.

# Entreprise GiftCard
# Déploiement dockers WordPress et MySQL

## Ajouter ce git à votre répertoire

Pour cela, il est nécessaire que vous installiez **Git** sur votre appareil, si vous ne l'avez pas vous pouvez le retrouver ici :

https://github.com/git-guides/install-git

Puis veuillez exécuter la commande suivante :

```git clone https://github.com/lunatiique/nf19-projet```

## Installer docker sur votre appareil

### Pour Linux

Veuillez-vous rendre ici :

https://docs.docker.com/desktop/install/linux-install/

### Pour Windows

Veuillez-vous rendre ici :

https://docs.docker.com/desktop/install/windows-install/

### Pour MacOS

Veuillez-vous rendre ici :

https://docs.docker.com/desktop/install/mac-install/


## Lancer le docker

Dans votre terminal, veuillez vous placer dans le dossier où se trouve le fichier *docker-compose.yml*.

Puis veuillez exécuter la commande suivante pour lancer le docker-compose.

```sudo docker compose up -d```

## Accéder au wordpress

### Visiter le Wordpress

Veuillez vous rendre à l'adresse  *localhost:8000*  sur votre navigateur internet préféré pour accéder et visiter le wordpress.

### Modifier le WordPress

Voici les identifiants de connexion du compte pour modifier le WordPress :

identifiant : lu-nf19

mot de passe : projetNF19

Veuillez-vous rendre à l'adresse suivante pour accéder à la personnalisation du Wordpress :

http://localhost:8000/wp-admin/

## Pour assurer la persistance des données

Lorsqu'il est pertinent que les autres membres puissent voir vos modifications, merci de bien penser à mettre les versions modifiées des volumes du docker stockés dans les dossiers suivants :

- *donnees*

- *site*

Vous pouvez faire ça avec les commandes suivantes dans votre terminal lorsque vous êtes placés dans le dossier du projet :

```git add donnees site```

```git commit -m '[message décrivant modifications apportées]'```

```git push```

## Arrêter le docker

Exécutez la commande suivante dans votre terminal pour arrêter le docker-compose.

```sudo docker compose down```
