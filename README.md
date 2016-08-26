# exobot
**ExoBot** est une solution clé en main pour les développeurs de Bots Discord. Le projet est écrit entièrement en Javascript, documenté et commenté en français.
Il utilise le module [discord.io](https://github.com/izy521/discord.io).

**NodeJS est obligatoire pour que le Bot puisse fonctionner.**

## Installation
#### Etape 1 : Installer NodeJS

- Rendez-vous sur la page des [téléchargements de NodeJS](https://nodejs.org/en/download/) ;
- Téléchargez la version compatible avec votre OS et installez-la ;

Si vous rencontrez des difficultés, [ce guide](https://openclassrooms.com/courses/des-applications-ultra-rapides-avec-node-js/installer-node-js) pourra vous aider.

#### Etape 2 : Créer une application Discord

Exobot ne se suffit pas à lui-même, vous aurez besoin de créer une application Discord.

- Rendez-vous sur la page [des applications Discord](https://discordapp.com/developers/applications/me) ;
- Cliquez sur `New Application` ;
- Indiquez le nom de votre Bot dans *APP NAME* ;
- (optionnel) Ajouter une description et un avatar pour votre Bot ;
- Validez les informations.

Depuis quelque temps, Discord permet de convertir les applications directement en Bot.
La conversion vous fournira un *token* permettant au Bot de se connecter sans avoir besoin d'adresse email, ni mot de passe.

- Cliquez maintenant sur `Create a Bot User` pour transformer votre application en Bot ;
- Maintenant que votre Bot est créé, il vous suffit de générer un *token* dans la partie *APP BOT USER*.

Vous voilà en posséssion du token, gardez cette page ouverte pour le moment.


#### Etape 3 : Ajouter le Bot à votre serveur

Bien entendu, vous devez avoir les droits nécessaires pour pouvoir ajouter un bot sur un serveur. Pour ce faire, vous aurez besoin de cette URL :

`https://discordapp.com/oauth2/authorize?client_id=client_id_ici&scope=bot&permissions=0`

- Remplacez maintenant `client_id_ici` par l'ID de votre Bot, disponible dans la partie *APP DETAILS* ;
- Sélectionnez le serveur où vous voulez ajouter le bot, puis validez.

Le Bot est maintenant ajouté au serveur.

#### Etape 4 : Lancer le bot

Vous aurez besoin d'installer le module `discord.io` pour pouvoir utiliser le exobot.

- [Téléchargez exobot](https://github.com/ewauq/exobot/archive/master.zip) et dézippez son contenu où vous le souhaitez ;
- Ouvrez l'invite de commande ou le terminal de votre OS ;
- Rendez vous à la racine du répertoire d'exobot que vous venez de dézipper ;
```
cd /chemin/de/exobot
```
- Installez discord.io :
```
npm install discord.io
```
- Et enfin, lancez le bot :
```
node run.js
```

A ce stade, tout devrait fonctionner normalement. 

## Où héberger le Bot ?

Libre à vous de choisir la méthode d'hébergement qui vous convient le mieux. Il existe de nombreux fournisseurs d'hébergements de serveurs NodeJS sur internet. Vous pouvez également l'héberger sur votre machine personnelle ou encore sur un Raspberry Pi.

## Comment ajouter des commandes ?

Un fichier `example.js` est disponible dans le répertoire `commands`. Il constitue une bonne base pour le développement d'une commande simple impliquant un message de retour de la part du Bot.

## (à venir)

- Documentation complète dans le wiki
