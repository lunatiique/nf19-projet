# Projet NF19 - A22

Réalisé par Luna Schenk et Lucas Sauron.

# Entreprise GiftCard
# Déploiement dockers WordPress et MySQL

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


## S'identifier sur le docker hub

*Si vous n'avez pas de compte docker hub, veuillez vous en créer un ici : https://hub.docker.com*

Exécutez la commande suivante :

```docker login```

Veuillez ensuite entrer votre nom d'utilisateur ainsi que votre mot de passe.

## Récupérer les images nécessaires 

Vous devez récupérer l'image de wordpress et de mysql utilisés pour votre déploiement.

Exécutez les commandes suivantes dans votre terminal.

```docker pull lunatique/wordpress-nf19```

```docker pull lunatique/mysql-nf19```

## Lancer le docker

Veuillez exécuter la commande suivante dans votre terminal pour lancer le docker-compose.

```docker compose up -d```

## Modifier le wordpress

### Se connecter

identifiant : lu-nf19

mot de passe : projetNF19

## Accéder au MySQL

## Arrêter le docker

Exécutez la commandea suivante dans votre terminal pour arrêter le docker-compose.

```docker compose down```